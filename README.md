# CashStarter
game.Players.PlayerAdded:Connect(function(Player) local leaderstats = Instance.new("folder") leaderstats.parent = Player  Local cash = Instance.new("NumberValue") cash.Name = "Cash" cash.Value = 500 cash.Parent = leaderstats  end)
