-- CODE BY NEX

local PlaceId = game.PlaceId

if PlaceId == 5602055394 then
	loadstring(game:HttpGet('https://gist.githubusercontent.com/blockrz/c026b0b8108b4486e9ac1bcf8df71134/raw/cad4c11295905dd47f80feea8ca76a91d0e9a026/DAHOODCONNECTOR'))()
elseif PlaceId == 2248408710 then
	loadstring(game:HttpGet("https://gist.githubusercontent.com/blockrz/9a1fd50545dd2b6c917c57372dab79c6/raw/6ab7891ae0688128c146e614b985342a7bee6262/DESTRUCTIONSIM"))()
elseif PlaceId == 155615604 then
	loadstring(game:HttpGet("https://gist.githubusercontent.com/blockrz/544668375548eb9b74cb7ab2e1d068f9/raw/ce9a59af4a2a78b32c9fb8f6842290d3baa5b56a/PRISONLIFECONNECTOR"))()
elseif PlaceId == 6284583030 then
	loadstring(game:HttpGet("https://gist.githubusercontent.com/blockrz/85d5ef77fded98f0b27184a79dc09538/raw/39a1c121257eac2972738e0edf6eafc83cfc81e2/PETSIMCONNECTOR"))()
elseif PlaceId == 5201688943 then
	loadstring(game:HttpGet("https://gist.githubusercontent.com/blockrz/3e05ee79e2c9b89fa99b879cd38c08e2/raw/0abaace309bdace861f4b51a554ce1494b3673b4/HOODAIMCONNECTOR"))()
elseif PlaceId == 286090429 then
	loadstring(game:HttpGet("https://gist.githubusercontent.com/blockrz/ffdcb6aa6f536663fafbd3a73d3d8c39/raw/c343cfe58c193cf16f8923781a69550ff875e7be/ARSENALCONNECTOR"))()

else
	game.Players.LocalPlayer:kick("Game not supported! Discord: https://discord.gg/jgeVyDF3Xz")
	wait(25)
	game:Shutdown()
end
