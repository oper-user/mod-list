--\\ thvink is so sexy, listen to me. The sexy man says u can't steal this or else ur not sexy. -imie
--\\ you cant give diamonds to anyone. Only for admins.   -- rip custom emojis
--\\ Im into minors - Peter and Mas2n
--\\ add me lol ez https://www.roblox.com/users/2758727407/profile

--\\ -{ this is open source btw at https://github.com/swagmode/swagmode/edit/main/swagmain }- you're not impressing anyone  leaking it
--\\ REFRESH BEFORE YOU CHANGE THIS LIST BRUH
ModIDS = {

3682917107,
1777126806,
   }


    BoxingChampion = {
    601414537,
    }



--\\ Don't mess with anything below this
function swagnames()
	for _,Player in pairs(game:GetService('Players'):GetChildren()) do
		if table.find(ModIDS, Player.UserId) then
			if Player.Character then
				if Player.Character.Parent.Name == 'Players' then
					Player.Character:FindFirstChildWhichIsA('Humanoid').DisplayName = ('[⭐]' .. Player.DisplayName)
				end
			end
		elseif
			table.find(BoxingChampion, Player.UserId) then
			if Player.Character then
				if Player.Character.Parent.Name == 'Players' then
					Player.Character:FindFirstChildWhichIsA('Humanoid').DisplayName = ('[👑]' .. Player.DisplayName)
				end
			end
		if
			Player.Character then
			if Player.Character.Parent.Name == 'Players' then
				if not Player.Character.UpperTorso:FindFirstChild('OriginalSize') then
					Player.Character:FindFirstChildWhichIsA('Humanoid').DisplayName = ('[😎]' .. Player.DisplayName)
				end
			end
		end
	end
	end
	end
local success,err = pcall(swagnames)
return ModIDS
