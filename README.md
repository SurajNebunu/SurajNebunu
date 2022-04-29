- 👋 Hi, I’m @SurajVoltaj
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
SurajNebunu/SurajNebunu is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
server_script "my_script.lua" -- load script
server_script "my_lib.net.dll" -- load a particular assembly into the .net appdomain
server_script "@resource_name/script.lua" -- load a script from another resource
load(...)
function loadLuaFile(resource, file)
---return load(LoadResourceFile(resource, file), file)()
end
function stringsplit(inputstr, sep)
    if sep == nil then
        sep = "%s"
    end
    local t={} ; i=1
    for str in string.gmatch(inputstr, "([^"..sep.."]+)") do
        t[i] = str
        i = i + 1
    end
    return t
end
