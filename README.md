_G.AutoFarm = true
while _G.AutoFarm do wait()
    pcall(function()
for i,v in pairs(game:GetService("Workspace").Collectables:GetDescendants()) do
    if v.ClassName == "Model" then
     v.Ring.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
            end
        end
    end)
end
