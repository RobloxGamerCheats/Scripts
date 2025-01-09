getgenv().Config = {
    ["EquipEnchants"] = {},
    ["KickWhenReachGoal"] = {
        ["Rank"] = 33,
        ["Rebirth"] = 9,
        ["Area"] = 239
    },
    ["StopAt"] = {
        ["Rank"] = 34, 
        ["Area"] = 239
    },

    ["AutoOpen"] = true,
    ["AutoBalloon"] = false,

    ["FPSBooster"] = true,
    ["UltraFPS"] = true,
    ["Webhook"] = "",
}
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/177d65e916988f4b84dd21ed33a2aa91.lua"))()
