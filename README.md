# Data-wow

Game data collected by the SeviathsUsefulTools addon (quests, loot, materials, items, NPCs, nodes, towns, guilds, nameplate and inspect records).

The `collected` folder is baked by `tools/bake_collected.py` of the addon and is shipped inside the addon itself: the addon cannot download anything while the game runs, so players receive this data with the addon.

One file per saved table: `<addon part>.<table>.lua`. The player records are public game data (names, realms, guilds, item levels, Raider.IO answers).
