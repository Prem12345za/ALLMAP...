local PlaceId = game.PlaceId

if PlaceId == 6284583030 then
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Prem12345za/PREMHUB-V.2/main/README.md"))()
elseif PlaceId == 4616652839 or PlaceId == 5447073001 or PlaceId == 5084678830 or PlaceId == 5431071837 or PlaceId == 5431069982 or PlaceId == 5943874201 then
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Prem12345za/PREM-KL/main/README.md"))()
elseif PlaceId == 537413528 then
else
	game.Players.LocalPlayer:kick("สคริปไม่มีเกมนี้ ไอ้เวร")
	wait(1)
	game:Shutdown()
end
