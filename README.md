# lua-modules / Import implimentation for Synapse X.

Put this script in your Synapse X autoexec folder.
```lua
local success, err = pcall(function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/ou1z/lua-modules/main/import.lua'))()
end)
if err then rconsoleprint(string.format([[
    Failed to load module "import"
    Error: %s
]], err)) return end
```

lua-modules usage:

```lua
import 'test'

test("hello") --> prints hello to the console
```
