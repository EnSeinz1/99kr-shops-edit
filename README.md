# 99kr-shops-edit
For make the shops working you need to put this line of code anywhere into es_extended/server/functions.lua "ESX.GetItemLimit = function(item) if ESX.Items[item] ~= nil then return ESX.Items[item].limit end end"
