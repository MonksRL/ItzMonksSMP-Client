# ItzMonksSMP Client

Official Fabric client installer for **ItzMonksSMP**.

The ItzMonksSMP Client adds the client-side support required by custom ItzMonksSMP features, including advanced name cosmetics, private cosmetic previews, and server client-verification.

## Current Versions

- **Minecraft:** 26.2
- **Mod Loader:** Fabric
- **Fabric Loader:** 0.19.5
- **Fabric API:** 0.160.0+26.2
- **Client:** v1.2.6 R10
- **Installer:** v2.2.7

## Features

The client supports:

- RGB player names
- Rainbow player names
- Gradient player names
- Solid custom colors
- Bold names
- Italic names
- Bold + Italic combinations
- RGB/Gradient + Bold/Italic combinations
- Matching cosmetic names in the TAB menu
- Matching cosmetic names above players' heads
- Matching cosmetic usernames in chat
- Private `/cosmetics` name previews
- Local preview rendering in TAB
- Local preview rendering above the previewing player's head
- Local preview rendering for the previewing player's own chat name
- Reliable ItzMonksSMP client verification using the dedicated `itzmonks:client` handshake

Temporary previews are **local to the player previewing them**. Other players continue to see that player's real equipped cosmetic. Purchased/equipped cosmetics are handled by the server and are visible normally to other players.

## Installation

1. Open the **Releases** section of this repository.
2. Download:

   `ItzMonksSMP-Client-Installer-FABRIC-v2.2.7.zip`

3. Extract the ZIP completely.
4. Fully close **Minecraft AND the Minecraft Launcher**.
5. Run:

   `Install ItzMonksSMP Client.bat`

6. Most players should leave the Minecraft folder set to:

   `%APPDATA%\.minecraft`

7. Click **INSTALL EVERYTHING**.
8. Wait for the installer to finish.
9. Re-open the Minecraft Launcher.
10. Select the **Fabric 26.2** installation.
11. Join ItzMonksSMP.

## What the Installer Does

Installer v2.2.7 is designed to make the setup truly one-click:

- Automatically installs Fabric Loader `0.19.5` for Minecraft `26.2`
- Creates/verifies the Fabric 26.2 installation in the Minecraft Launcher
- Installs Fabric API `0.160.0+26.2`
- Installs `ItzMonksCosmeticsClient-1.2.6-mc26.2-FABRIC-R10-HandshakeFix.jar`
- Removes older `ItzMonksCosmeticsClient*.jar` versions
- Leaves unrelated Fabric mods alone
- Supports custom Minecraft game directories
- Verifies the installed client JAR with SHA-256
- Verifies that the Fabric launcher installation/profile actually exists before reporting success

Unlike installer v2.2.6, v2.2.7 does **not** require the player to manually use a separate Fabric Installer window.

## Custom Minecraft Game Directory

Most players should use:

`%APPDATA%\.minecraft`

If your Minecraft profile uses a custom **Game Directory**, click **Browse** in the installer and select the folder that contains that profile's `mods` folder.

## Manual Installation

Advanced users can manually place the current client JAR into:

`%APPDATA%\.minecraft\mods`

Current client JAR:

`ItzMonksCosmeticsClient-1.2.6-mc26.2-FABRIC-R10-HandshakeFix.jar`

You must also be using Minecraft 26.2 with Fabric Loader and Fabric API.

## R10 Client Changes

R10 includes the current cosmetics/client fixes:

- Uses the dedicated `itzmonks:client` plugin-message channel for reliable server verification
- Keeps the older Minecraft brand handshake as a fallback
- Keeps private/local cosmetic previews working in TAB and above the player's head
- Keeps the previewing player's local chat-name preview working
- Prevents temporary previews from becoming public cosmetics

## Installer v2.2.7 Changes

- Automatically installs Fabric instead of opening a separate Fabric Installer window
- Verifies the actual Minecraft Launcher Fabric installation/profile
- Fixes cases where Fabric files existed but no Fabric installation appeared in the launcher
- Improves custom game-directory handling
- Requires Minecraft and the Minecraft Launcher to be fully closed during installation

## Troubleshooting

### Fabric does not appear in Minecraft Launcher

Make sure:

- Minecraft and the Minecraft Launcher were completely closed while the installer ran
- You selected the correct Minecraft game directory
- The installer reached **Installed successfully**

Then reopen the launcher and look for the Fabric 26.2 installation.

### The server says the client is not installed

Make sure:

- You are launching Minecraft 26.2
- You launched the Fabric installation
- `ItzMonksCosmeticsClient-1.2.6-mc26.2-FABRIC-R10-HandshakeFix.jar` is inside your `mods` folder
- There is only one `ItzMonksCosmeticsClient*.jar` in the `mods` folder

### Minecraft crashes or the client does not work

Send the newest file from:

`%APPDATA%\.minecraft\logs\latest.log`

If Minecraft generated a crash report, also send the newest file from:

`%APPDATA%\.minecraft\crash-reports`

### The installer fails

Run the installer again and click **View Log**.

Installer log:

`%TEMP%\ItzMonksSMP-Fabric-Installer.log`

## Updating

When a new ItzMonksSMP Client installer is released:

1. Download the newest installer from **Releases**.
2. Fully close Minecraft and the Minecraft Launcher.
3. Run the new installer.
4. The installer automatically removes older ItzMonksSMP Client JARs and installs the current one.

## Important

Always download the ItzMonksSMP Client from the official repository.

**Repository:** `MonksRL/ItzMonksSMP-Client`
