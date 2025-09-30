loadstring(game:HttpGet(("https://raw.githubusercontent.com/daucobonhi/Ui-Redz-V2/refs/heads/main/UiREDzV2.lua")))()

       local Window = MakeWindow({
         Hub = {
         Title = "chicken tempest",
         Animation = "hello kitty"
         },
        Key = {
        KeySystem = false,
        Title = "Key System",
        Description = "",
        KeyLink = "",
        Keys = {"1234"},
        Notifi = {
        Notifications = true,
        CorrectKey = "Running the Script...",
       Incorrectkey = "The key is incorrect",
       CopyKeyLink = "Copied to Clipboard"
      }
    }
  })

       MinimizeButton({
       Image = "https://pin.it/6WSqEowei",
       Size = {60, 60},
       Color = Color3.fromRGB(10, 10, 10),
       Corner = true,
       Stroke = false,
       StrokeColor = Color3.fromRGB(255, 0, 0)
      })
      
------ Tab
     local Tab1o = MakeTab({Name = "Script Farm"})
     local Tab2o = MakeTab({Name = "kaitun"})
------- BUTTON
    
    AddButton(Tab1o, {
     Name = "blue x blue",
    Callback = function()
	  local Settings = {
  JoinTeam = "Pirates"; -- Pirates/Marines
  Translator = true; -- true/false
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/Dev-BlueX/BlueX-Hub/refs/heads/main/Main.lua"))()

    AddButton(Tab2o, {
     Name = "xero kaitun",
    Callback = function()
	  local Settings = {
  JoinTeam = "Pirates"; -- Pirates/Marines
  Translator = true; -- true/false
}

getgenv().Team = "Pirates"
getgenv().Config = {
    ["Farm"] = {
        ["Skip Level"] = true,
        ["Raids"] = { 
            ["Lock Fragment"] = 15000,
            ["Awakening Fruit"] = false
        },
        ["Lock Race"] = {},
        ["Evo Race"] = true
    },
    ["Quest"] = {
        ["Citizen Quest"] = true,
        ["RGP Color"] = true,
        ["Pull Lever"] = false
    },
    ["Item"] = {
        ["Get Pole"] = false,
        ["Get Saber"] = true,
        ["Get Soul Cane"] = true,
        ["Get Bisento"] = true,
        ["Get Rengoku"] = true,
        ["Get Midnight Blade"] = true,
        ["Skull Guitar"] = true,
        ["Cursed Dual Katana"] = true,
        ["Get Kabucha"] = true,
        ["Get Mirror Fractal when have God's Chalice"] = true,
        ["Collect Berries"] = false
    },
    ["Settings"] = {
        ["FPS Boost"] = true,
        ["Black Screen"] = false,
        ["Method"] = "Half", -- Mastery Sword
        ["Buy Zoro Sw"] = false,
        ["Bring Range"] = 350,
        ["Hop if any player is nearby"] = true
    },
    ["Fruit"] = {
        ["Select Fruit"] = "", -- Dough-Dough
        ["Snipe Fruit"] = false
    }
} 
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/ca16cb42816b395e079fa7a114352ba9.lua"))()