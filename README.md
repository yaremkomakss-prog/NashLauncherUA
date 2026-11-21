# NashLauncherUA — starter project

This is an Electron desktop UI prototype, not yet a complete Minecraft launcher.

## Run on Windows
1. Install Node.js LTS.
2. Extract this folder.
3. Open PowerShell in this folder.
4. Run: `npm install`
5. Run: `npm start`

## Build a Windows installer
Run: `npm run dist`

## Current prototype features
- Ukrainian, Russian and English UI selector
- Nickname and Minecraft version required before the Play action
- Requested validation dialogs with OK / Cancel
- Loader selector: Vanilla, Forge, NeoForge, Fabric, Quilt
- Theme color palette and custom color
- Navigation for mods, friends, visuals and settings

## Not implemented yet
- Microsoft account authentication and official game asset/library downloads
- Actual Minecraft process launch and per-version loader installation
- Real skin lookup and friends backend/chat/voice
- In-game client/mod integration (Right Shift menu, HUD, minimap, waypoints)
- Modpack/catalog downloads and profile management

These require a secure launcher backend, Microsoft/Xbox authorization flow, game library handling, and separate Minecraft-side mods/services. Do not enter Microsoft credentials into this prototype.
