local PlaceId = game.PlaceId


        

if PlaceId == 6329844902 then -- Last Pirates 
	loadstring(game:HttpGet('https://raw.githubusercontent.com/kickTh/SomeHub/main/Last%20Pirates.lua.txt', true))()
end

else
	game.Players.LocalPlayer:kick("Error Script ")
	wait(1)
	game:Shutdown()
end
