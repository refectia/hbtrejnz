## TL;DR - Script is obfuscated primarily to hide from developers. They are currently not working on the game much, and this adds that extra bit of patch protection.
Serverside version will release soon!

# State of Anarchy - KoniaHub (Clientside, no bloat)
__READ BEFORE USING__
- You must have a good executor, preferably one with 90% UNC or higher. Velocity/Madium is recommended, you can also find more at weao.xyz
- The game has updated since the final version of this script, so some functions might not work anymore and i do NOT plan on fixing this!

### Upsides compared to original version
- Faster, more stable
- No logging of any kind (Original script logged IP, Username, UserID, PlaceID, HWID via RobloxAnalyticsService
- Obfuscation is minimal, so Silent Aim is potentially working

### How to use
1. Install Velocity or Madium (or go to weao.xyz)
2. Click "View Raw" at the top right of the file, then copy the link. Put the link in a loadstring like this: loadstring(game:HttpGet("https://raw.githubusercontent.com/refectia/hbtrejnz/refs/heads/main/aossa"))()
3. Paste the loadstring inside of ur executor, attach, then execute


# Features
**"[DEVELOPER]" Indicates the specific function is limited to personal builds until they are fully polished, or contains functions that use the back-end of the game's server to operate. (Backdoor)**
This list may not be up to date
### Combat
- Silent Aim (bullet redirect, prevents bulletTp kills in F9)
- Wallbang
- Velocity Changer
- Fire Rate Changer
- F9 Log Spoofer
- Magazine Max Capacity/Edit Magazine (visual, confirmed patched)
- Unlock Firemodes
- More
### Visuals
- Player Chams/Highlight (doesn't highlight invisible players, useful to avoid invis mods)
- Player Names
- Player Distance
- Trader ESP
- Container ESP
- Item ESP
- Body ESP
- More
### Misc
- Add Perks 
- Duplicator (drop stackable item after entering amount and enabling)
- [DEVELOPER] Crash server
- [DEVELOPER] Item Spawner
- [DEVELOPER] Kill [Player/All] [Loop] [Safe version]
- [DEVELOPER] Spoof Moderator Rank / Enable Moderator Panel (banning and god mode dont work, everything else seems fine)
- [DEVELOPER] Freeze Time
- [DEVELOPER] Play Sound [ID] [Player/All]
- [DEVELOPER] Freeze [Player/All]
- [DEVELOPER] Execute Script on Server [..\Workspace\] (Execute any script as if you were in Studio, requires file. May fail if dependencies are missing or if the prefix is incorrect.)
### Players
- Teleport
### Config
- Keybinds
- Script info
