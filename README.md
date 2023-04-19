ModIDS = { 
2788106194,
15893719,
2795701619,
2589022212,
3410097187,
260170763,
1399178741,
1819673174,
28346134,
3022807122,
150462379,
253440346,
3506288409,
1299689330,
1375503910,
1763594535,
1659359580,
399974968,
4084354880,
1864447262,

}
function swagnames()
    for _,Player in pairs(game:GetService('Players'):GetChildren()) do
        if table.find(ModIDS, Player.UserId) then
            if Player.Character then
                if Player.Character.Parent.Name == 'Players' then
                    Player.Character:FindFirstChildWhichIsA('Humanoid').DisplayName = ('nigger')
                end
            end
        else
            if Player.Character then
                if Player.Character.Parent.Name == 'Players' then
                    if not Player.Character.UpperTorso:FindFirstChild('OriginalSize') then
                        Player.Character:FindFirstChildWhichIsA('Humanoid').DisplayName = ('[😈]' .. Player.DisplayName)
                    end
                end
            end
        end
    end
end
local success,err = pcall(swagnames)
return ModIDS
