# Max Payne 1 VR

☕ Support on Ko-fi: [https://ko-fi.com/evilsheep](https://ko-fi.com/evilsheep)

[Download the beta](https://github.com/evilSheep/max-payne-1-vr/releases)

[YouTube channel](https://www.youtube.com/@1EvilSheep1)

**A free PC VR mod for the original Max Payne.**

Play as Max with tracked hands, physical weapons, manual reloading and bullet-time combat in VR.

> **This is a beta.** Reports from
> different headsets and PC setups are what the beta is for - see [Reporting problems](#reporting-problems).

## Features

- Full stereoscopic VR with head tracking, motion controls and roomscale movement.
- A visible body that follows your head and hands.
- Independent aiming and dual wielding, physical jacket holsters and a shoulder holster for long guns.
- Manual magazine, slide, pump and shell reloading, plus physical painkiller use.
- Bullet time and shoot dodges.
- Punches, gun melee, enemy disarming, and grabbing and throwing ragdolls. A body you hold up stops enemy bullets.
- Grenades and Molotovs thrown by hand.
- Physical rifle scope with an eye-lock setting (on by default).
- Gore: bullet wounds with flesh and bone inside, blood that runs and pools, and dismemberment (can be turned off).
- Gun spinning, an optional weapon wheel, and stick actions for jumping, crouching and bullet time.
- Wrist HUD, weapon ammo displays and a virtual screen for menus and cutscenes.
- 4K textures: the "25th Anniversary Remaster" pack by andrew22, included with his permission (can be turned off).
- One-click installer, including the 4 GB memory patch the 4K textures need.

## Melee

- You must swing hard enough for enemies to react to melee hits.
- Standard enemies take 5 hits to kill unarmed, 3 hits to kill if using a weapon.
- A 3 hit unarmed combo (2 hits with a weapon) will stagger an enemy, at which point you can disarm them by grabbing
  their weapon.
- You can also disarm an enemy while shoot dodging, or after throwing a weapon at them to stagger them.

## Holsters

- Gun holsters are located on your lower chest on either side.
- Long guns go in the shoulder holster on your right shoulder.
- Ammo can be grabbed from either hip.
- Painkillers can be grabbed from your upper chest; bring the bottle to your mouth to take one.
- Grenades and Molotovs are on your left shoulder.

## Requirements

- Your own installed copy of **Max Payne** from **Steam** (version 1.05).
- A Windows 10/11 gaming PC with SteamVR installed.
- A PC-connected VR headset and two tracked controllers. Development testing used **PSVR2** and **Quest 3 through
  Virtual Desktop**. This is not a standalone Quest application.
- For the optional 4K textures: about 4 GB of free disk space.

PSVR2 adaptive triggers use the optional **PSVR2 Toolkit**, installed separately. Standard controller vibration does
not require the toolkit.

## Download and install

Download the files from this repository's **Releases** page. The **Code → Download ZIP** button downloads the
documentation, not the mod.

1. Install the game through Steam, run it once, then close it.
2. Download `MaxPayneVR-v<version>.zip`. For the 4K textures (optional, 3.7 GB), also download the three
   `MaxPayneVR-4K-Textures-part*.zip` files into the same folder.
3. Extract `MaxPayneVR-v<version>.zip` there. Leave the texture zips zipped.
4. Double-click **Install Max Payne VR.cmd** and press **Install**. Wait for it to finish; unpacking the textures can
   take a few minutes. Without the texture zips, the 4K textures box is greyed out and the game keeps its original
   textures.
5. Start SteamVR, then launch Max Payne from Steam.

Open **Options > VR Settings** in the game to customize the experience. See the [installation guide](INSTALLATION.md)
and [controller guide](CONTROLS.md) for details.

To update, run the installer from the new release. To remove the mod, run the installer and press **Uninstall**. Your
saves are kept, and the installer asks whether to keep your VR settings and calibrations.

## FAQ

**The SteamVR menu is stuck in front of me and I can't close it.**
Steam is showing Max Payne in **Desktop Game Theatre**, its mode for flat games, and that keeps the SteamVR menu open
over the VR game. Turn it off for Max Payne:

1. Quit the game.
2. In your Steam **Library**, right-click **Max Payne** and choose **Properties**.
3. On the **General** page, turn off **Use Desktop Game Theatre while SteamVR is active**.
4. Start the game again.

**I ran "Verify integrity of game files" in Steam and the mod stopped working.**
Steam puts its own `maxpayne.exe` back, without the 4 GB patch. Run the installer again and press **Install**.

## Reporting problems

Use this repository's **Issues** page. Include the mod version, headset, PC VR connection method, level, what happened
and how to reproduce it. Attach `maxpaynevr.log` from the game folder (Steam > right-click Max Payne > Manage > Browse
local files), copied right after the problem: it is overwritten each time the game starts. For performance problems,
include your CPU, GPU and VR resolution.

## Credits and distribution

Mod by **evilSheep**. Third-party software credits and license notices are included in [LICENSE.txt](LICENSE.txt)
and [licenses](licenses/).

The 4K textures are the **"25th Anniversary Remaster"** by **andrew22**
([Nexus Mods](https://www.nexusmods.com/maxpayne/mods/45)), included in the release with his permission. All credit
for the textures goes to andrew22; see [licenses/4K-Textures.txt](licenses/4K-Textures.txt).

The gore system's inner skeleton is built from "Low Poly Skeleton For Maya" by
[606tom](https://www.renderhub.com/606tom) (RenderHub Extended Use License) and "Human Skull" by CDmir (CC0), both
modified; see [licenses/Gore-assets.txt](licenses/Gore-assets.txt).

Claude AI was used during development to assist with coding, debugging, research, and documentation. **evilSheep**
directs the project and tests the mod in-game, with community feedback helping identify issues across different
headsets and PC setups. **evilSheep** is responsible for what ships, including any bugs.

The download contains mod software, licensed dependencies and andrew22's textures. No original Max Payne game files
are included: the mod works with your own installation.

This repository hosts documentation and releases; the VR runtime development source is not included. This is an
unofficial fan project, not affiliated with or endorsed by Remedy Entertainment, Rockstar Games or Take-Two
Interactive. Game names and trademarks belong to their respective owners.
