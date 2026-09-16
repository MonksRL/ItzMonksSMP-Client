# ItzMonksSMP Client

Official Fabric client installer for **ItzMonksSMP**.

The ItzMonksSMP Client is used for custom server features that require client-side support, including advanced player-name cosmetics.

## Features

The client enables support for:

- RGB player names
- Rainbow player names
- Gradient player names
- Bold names
- Italic names
- Bold + Italic combinations
- RGB/Gradient + Bold/Italic combinations
- Matching cosmetic names above players' heads
- Client verification when joining ItzMonksSMP

The client works alongside the server's `/cosmetics` system.

## Current Version

- **Minecraft:** 26.2
- **Mod Loader:** Fabric
- **Client:** v1.2.3 R7
- **Installer:** v2.2.5

## Installation

1. Go to the **Releases** section of this repository.
2. Download the latest:

   `ItzMonksSMP-Client-Installer-FABRIC-v2.2.5.zip`

3. Extract the ZIP completely.
4. Close Minecraft if it is currently running.
5. Run:

   `Install ItzMonksSMP Client.bat`

6. Most players should leave the Minecraft folder set to:

   `%APPDATA%\.minecraft`

7. Click **INSTALL EVERYTHING**.
8. Wait for the installer to finish.
9. Launch the **Fabric 26.2** Minecraft profile.
10. Join ItzMonksSMP.

## What the Installer Does

The installer will:

- Install the required ItzMonksSMP Fabric client mod
- Install/check the required Fabric setup
- Install/check Fabric API
- Remove older ItzMonksSMP Client versions
- Keep your other Minecraft mods
- Verify that the correct client file was installed

It does **not** delete your other Fabric mods.

## Custom Minecraft Game Directory

Most players use:

`%APPDATA%\.minecraft`

If your Minecraft installation uses a custom **Game Directory**, click **Browse** in the installer and select the folder containing your `mods` folder.

## Manual Installation

Advanced users can manually install the client mod into:

`%APPDATA%\.minecraft\mods`

The current client file is:

`ItzMonksCosmeticsClient-1.2.3-mc26.2-FABRIC-R7.jar`

You must also have the correct Fabric setup for Minecraft 26.2.

## Troubleshooting

### The server says the client is not installed

Make sure you are launching:

- Minecraft 26.2
- Fabric Loader
- The latest ItzMonksSMP Client

Your `mods` folder should contain only one ItzMonksSMP client JAR.

### Minecraft crashes

Send the newest file from:

`%APPDATA%\.minecraft\logs\latest.log`

If Minecraft generated a crash report, also send the newest file from:

`%APPDATA%\.minecraft\crash-reports`

### The installer fails

Run the installer again and use the **View Log** option to check what failed.

## Updating

When a new ItzMonksSMP Client version is released:

1. Download the newest installer from **Releases**.
2. Close Minecraft.
3. Run the new installer.
4. The installer will replace the older ItzMonksSMP Client automatically.

## Important

Always download the ItzMonksSMP Client from this official repository.

**Repository:** MonksRL/ItzMonksSMP-Client
