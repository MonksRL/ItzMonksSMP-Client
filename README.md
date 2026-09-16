# ItzMonksSMP Client

Official Fabric client installer for **ItzMonksSMP**.

The ItzMonksSMP Client adds the client-side support required by custom ItzMonksSMP features, including advanced name cosmetics, private cosmetic previews, and server client-verification.

## Current Versions

- **Minecraft:** 26.2
- **Mod Loader:** Fabric
- **Fabric Loader:** 0.19.5 or newer
- **Fabric API:** 0.160.0+26.2 or newer compatible 26.2 build
- **Client:** v1.2.6 R10
- **Installer:** v2.2.6

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

   `ItzMonksSMP-Client-Installer-FABRIC-v2.2.6.zip`

3. Extract the ZIP completely.
4. Fully close Minecraft.
5. Run:

   `Install ItzMonksSMP Client.bat`

6. Most players should leave the Minecraft folder set to:

   `%APPDATA%\.minecraft`

7. Click **INSTALL EVERYTHING**.
8. Wait for the installer to finish.
9. Launch the **Fabric 26.2** Minecraft profile.
10. Join ItzMonksSMP.

## What the Installer Does

The installer:

- Installs `ItzMonksCosmeticsClient-1.2.6-mc26.2-FABRIC-R10-HandshakeFix.jar`
- Checks for a Fabric 26.2 launcher profile
- Opens the official Fabric installer if Fabric is missing
- Checks/installs Fabric API `0.160.0+26.2`
- Removes older `ItzMonksCosmeticsClient*.jar` versions
- Leaves unrelated Fabric mods alone
- Verifies the installed client JAR with SHA-256

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

## R10 Changes

R10 includes the latest cosmetics/client fixes:

- Uses the dedicated `itzmonks:client` plugin-message channel for reliable server verification
- Keeps the older Minecraft brand handshake as a fallback
- Keeps private/local cosmetic previews working in TAB and above the player's head
- Keeps the previewing player's local chat-name preview working
- Prevents temporary previews from becoming public cosmetics

## Troubleshooting

### The server says the client is not installed

Make sure:

- You are launching Minecraft 26.2
- You launched the Fabric profile
- `ItzMonksCosmeticsClient-1.2.6-mc26.2-FABRIC-R10-HandshakeFix.jar` is inside your `mods` folder
- There is only one `ItzMonksCosmeticsClient*.jar` in the `mods` folder

### Minecraft crashes or the client does not work

Send the newest file from:

`%APPDATA%\.minecraft\logs\latest.log`

If Minecraft generated a crash report, also send the newest file from:

`%APPDATA%\.minecraft\crash-reports`

### The installer fails

Run the installer again and click **View Log** to see what failed.

## Updating

When a new ItzMonksSMP Client version is released:

1. Download the newest installer from **Releases**.
2. Fully close Minecraft.
3. Run the new installer.
4. The installer automatically removes older ItzMonksSMP Client JARs and installs the current one.

## Important

Always download the ItzMonksSMP Client from the official repository.

**Repository:** `MonksRL/ItzMonksSMP-Client`
