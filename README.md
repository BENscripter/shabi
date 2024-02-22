local Luxtl = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Luxware-UI-Library/main/Source.lua"))() 
  
local Luxt = Luxtl.CreateWindow("Ver 0.25", 6105620301)    

local Examples = Luxt:Tab("Auto Pull Box") 
local ff = Examples:Section("Make u Auto Pull Box") 
ff:Label("Auto Farm")
ff:Button("Press", function()
    while wait(3) do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-368.802948, 45.253418, 333.306549, -0.795390785, -6.4954186e-08, -0.606096923, -9.8958516e-08, 1, 2.26968684e-08, 0.606096923, 7.80313343e-08, -0.795390785)
    break
end


while wait(3) do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-216.375275, 45.253418, 234.591629, -0.273245335, 5.03321651e-09, -0.961944342, -2.40478615e-09, 1, 5.91542815e-09, 0.961944342, 3.92963351e-09, -0.273245335)
     break
end

while wait(3) do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-288.768219, 45.253418, 475.157806, 0.0644796118, -8.80472655e-08, 0.997919023, -5.93761982e-08, 1, 9.20674026e-08, -0.997919023, -6.51891128e-08, 0.0644796118)
     break
end

while wait(3) do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-257.089325, 45.253418, 163.09848, -0.0283741653, -4.6642441e-08, -0.999597371, -1.38584451e-08, 1, -4.62678464e-08, 0.999597371, 1.25400534e-08, -0.0283741653)
     break
end

while wait(3) do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-331.598663, 45.253418, 286.438202, 0.0424613431, 4.0722238e-08, 0.999098122, 8.08421348e-08, 1, -4.41947634e-08, -0.999098122, 8.26457907e-08, 0.0424613431)
     break
end


while wait(3) do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-320.979309, 19.8034077, 290.283936, 0.836486042, 1.4470386e-09, 0.547988296, -1.10818388e-09, 1, -9.49031631e-10, -0.547988296, 1.86579918e-10, 0.836486042)
     break
end




end)

ff:Label("speed Settings")
ff:Button("X2", function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 28
end)

ff:Button("X3", function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 41
end)

ff:Button("X5", function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
end)

ff:Button("X7", function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 147
end)

ff:Button("X9", function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 240
end)

ff:Button("X11", function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 310
end)



ff:Button("Reset Speed!", function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 14
end)

ff:Label("Instant Interact")
ff:Button("Press", function()
game:GetService("ProximityPromptService").PromptButtonHoldBegan:Connect(function(prompt)
  fireproximityprompt(prompt)
end)
 
local Examples = Luxt:Tab("Log")
local ff = Examples:Section("Check What Feuture [NEW]") 

ff:Label("V0.1")
ff:Label("ADDED X2---X7 SOON X9")
ff:Label("Key System Soon Might Be Hard If Bypassing Or Share Keys To Anyone!")
ff:Label("Moving To Next Script after 0.6")
ff:Label("Updated Was From 2/22/1:41")

ff:Label("-------------------------------")
ff:Label("V0.2")
ff:Label("Added X11 and X9 Speed Also Added Instant Interact for Farm")
ff:Label("And Reduce reset speed")
ff:Label("Resets Key System")
ff:Label("Updated Was From 2/22/8:09")
ff:Label("-------------------------------")
ff:Label("V.25")
ff:Label("Fixed Main Update num")
ff:Label("Added  Instant Sry Forgotten")
ff:Label("Delay 2 or 1 day for updates")
ff:Label("Updated Was From 2/22/8:13")
