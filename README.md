# Driving System by Varco4961_ — licences

`licenses.json` is the list of Roblox experiences licensed to run the Driving System.
The system reads it at every server start (HttpService → raw.githubusercontent.com).

- `games`: game ids (`game.GameId`) of licensed experiences
- `creators`: Roblox user ids; every game they own is licensed
- `groups`: Roblox group ids; every game the group owns is licensed
- `revoked`: game ids that are never licensed (wins over the lists above)
- `message`: what an unlicensed game shows its players

Edits take effect within a few minutes, at the next server start.
