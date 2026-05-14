# State of Anarchy - JiggleHub (Clientside, de-obfuscated, no bloat, KoniaHub Remastered)
__READ BEFORE USING__
- You must have a good executor, preferably one with 90% UNC or higher. Velocity/Madium is recommended, you can also find more at weao.xyz
- The game has updated since the final version of this script, so some functions might not work anymore and i do NOT plan on fixing this! You may still open an Issue if you encounter a problem.

### Upsides compared to original version
- Faster, more stable
- No logging of any kind (Original script logged IP, Username, UserID, PlaceID, HWID via RobloxAnalyticsService
- Fully Open-Source, meaning you can use this as is, or use it for your own project.

### How to use
1. Install Velocity or Madium (or go to weao.xyz)
2. Click "View Raw" at the top right of the file, then copy the link. Put the link in a loadstring like this: loadstring(game:HttpGet("https://raw.githubusercontent.com/refectia/hbtrejnz/refs/heads/main/aossa"))()
3. Paste the loadstring inside of ur executor, attach, then execute


## Features
This list may not be up to date. You can review the code yourself to look for certain features.
NOTE: For weapon stat modification, you are required to enable the mod, enter a value, then drop your weapon/item and pick it back up. This applies (but not limited to) to Velocity changer, Fire Rate Changer, Unlock Firemodes, Magazine Capacity, Duplicator
### Combat
- Silent Aim | bullet redirect, prevents bulletTp/Freecam kills in F9)
- Wallbang
- Bullet Velocity Changer
- Fire Rate Changer
- F9 Log Spoofer
- Magazine Max Capacity/Edit Magazine | visual, confirmed patched
- Unlock Firemodes
- More
### Visuals
- Player Chams/Highlight | Includes Invisible check, will not highlight invis moderators. This makes it easier to avoid being banned during an ESP check :)
- Player Names
- Player Distance
- Trader ESP
- Container ESP
- Item ESP
- Body ESP
- More
### Misc
- Add Perks 
- Duplicator
### Players
- Teleport
### Config
- Keybinds
- Script info
- Terminate Script | Resets metatable, deletes any visuals/overlays, disables everything, then deletes the UI. May cause issues if you execute again after terminating.


# Mod Detector 
- Can be used with low-level or external executors (Xeno, Solara)
- This works on any game! Simply change the GroupID to the target group. If the game doesn't have a group, use UserID/Alt Detector instead.

## Features
- Resend notification (F2)
- Toggle UI Glow (F3) | Not Working, used as test for UI Integration but wasn't removed
- AutoKick/AutoLeave (F4) | Kicks you out of the game when a moderator is detected
- Mod Detector (F5) | Mod Detector Toggle
- UserID Detector/Alt Detector (F6) | Treats UserIDs in the GitHub repo as moderators. Meant for detecting moderator alts/games without groups
- Respawn persistence (F7) | Toggles respawn persistence. When on, mod detector will notify you of a mod in ur server every time you respawn.
- Terminate Script (F8) Terminates the script

## How to Use
1. Create a GitHub repository | Alternates: Pastebin, Filebin, Traff.co, Discord File Link (temporary)
2. Create a file (can be left empty, but it is required)
3. Click the file, then click "View Raw"
4. Copy the link (should look like __*https://raw.githubusercontent.com/...*__)
5. Paste the link into the URL field in the mod detector

**UserID Format**:
123456789, 000000000, 111111111, 987654321
