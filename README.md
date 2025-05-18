local hrp = game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart")
if hrp then
    local pos = tostring(hrp.CFrame)
    game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "CFrame Atual";
        Text = pos;
        Duration = 10
    })
end
