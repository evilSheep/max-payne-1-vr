# Installation

You need Max Payne from Steam (version 1.05), Windows 10/11, and a headset with controllers connected through SteamVR.

1. Install Max Payne through Steam, run it once, then close it.
2. From **Releases**, download `MaxPayneVR-v<version>.zip` and the three `MaxPayneVR-4K-Textures-part*.zip` files into
   one folder.
3. Extract `MaxPayneVR-v<version>.zip` in that folder. Leave the texture zips as they are; the installer reads them
   from beside the extracted folder.
4. Double-click **Install Max Payne VR.cmd** and press **Install**. Windows may ask for administrator rights, since the
   game is under Program Files. The installer finds the game through Steam.
5. Wait for it to finish. Unpacking the textures can take a few minutes.
6. Start SteamVR, then launch Max Payne from Steam.

Adjust your preferences in **Options > VR Settings** in the game.

## What the installer does

- Copies the mod (`d3d8.dll`, `maxpaynevr.asi`, `maxpaynevr_triggers.exe`) and its settings file
  (`maxpaynevr.ini`) into the game folder. Your settings are kept when you reinstall.
- Applies the **4 GB patch**: `maxpayne.exe` is unpacked from Steam's DRM wrapper with
  [Steamless](https://github.com/atom0s/Steamless) and given 4 GB of memory instead of 2 GB, which the 4K textures
  need. Steamless is downloaded from GitHub once, checked against a fixed SHA-256. The Steam exe is kept as
  `maxpayne.exe.steamstub`.
- Adds **VR Settings** to the game's Options menu.
- Installs the 4K textures into the game's `mp1vr_hd` folder.
- Copies starting calibrations for the guns. Any you already have are kept.

The game also needs Microsoft's **DirectX End-User Runtime** (`d3dx9_43.dll`). The installer tells you if it is
missing and offers Microsoft's download page.

## 4K textures

The "25th Anniversary Remaster" textures by andrew22
([Nexus Mods](https://www.nexusmods.com/maxpayne/mods/45)), included with his permission. They are on by default.

To use the original textures, turn off **Options > VR Settings > 4K Textures** and restart the game (the switch
happens when the game starts). Or run the installer again, untick **4K textures** and press **Install**. Either way,
switching back is instant: the pack stays in the `mp1vr_hd` folder.

## VR resolution

**Options > VR Settings > Display > VR Resolution** sets how many pixels tall each eye renders, from 1440 to 3456;
the width follows your headset's shape. **Headset Default** uses SteamVR's recommended resolution. Restart the game
to apply a change.

## Updating and removing

To update, run the installer from the new release and press **Install**.

To remove the mod, run the installer and press **Uninstall**. It puts the Steam exe back and removes the mod and the
textures. It asks whether to also delete your VR settings and calibrations. Your game saves are not touched.

## After "Verify integrity of game files" in Steam

Steam puts its own `maxpayne.exe` back, without the 4 GB patch. Run the installer again and press **Install**.
