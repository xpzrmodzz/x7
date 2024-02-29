--create by FRITE--
while true do wait()
local args = {
    [1] = {
        ["multiply"] = 7,
        ["action"] = "hit",
        ["enemyHum"] = workspace.dummies.TrainingDummy7.Humanoid
    }
}

game:GetService("ReplicatedStorage").DamageEvent:FireServer(unpack(args))
end
