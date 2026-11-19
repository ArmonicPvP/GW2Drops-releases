# GW2Drops collector downloads

[![Latest release](https://img.shields.io/github/v/release/ArmonicPvP/gw2drops?include_prereleases&sort=semver&label=release)](https://github.com/ArmonicPvP/gw2drops/releases/latest)
[![Discord](https://img.shields.io/discord/1571860503561506916?label=Discord&logo=discord&logoColor=white&color=5865F2)](https://discord.gg/ku3jxx48Vh)

GW2Drops records what drops from what in Guild Wars 2 and shows it on
[gw2drops.com](https://gw2drops.com). This repository only hosts the collector
download; the source code is private.

## Install

GW2Drops runs as an [arcdps](https://www.deltaconnected.com/arcdps/) extension, so
arcdps must be installed first.

1. Download `gw2drops_collector.dll` from the
   [latest release](https://github.com/ArmonicPvP/GW2Drops-releases/releases/latest).
2. Optional: check the download against the SHA-256 listed in the release notes
   (PowerShell: `Get-FileHash .\gw2drops_collector.dll`).
3. Close Guild Wars 2.
4. Put `gw2drops_collector.dll` in your Guild Wars 2 folder: the folder that
   contains `Gw2-64.exe`. That is usually `C:\Program Files\Guild Wars 2`, or
   `C:\Program Files (x86)\Steam\steamapps\common\Guild Wars 2` for Steam.
5. Start the game. A small **GW2Drops** window offers **Link to gw2drops.com**.
   Nothing is uploaded until you link.

To update, close the game and replace the DLL. To uninstall, close the game and
delete the DLL. Your recordings stay on your PC in `%LOCALAPPDATA%\GW2Drops`.

## Help

Join the [Discord](https://discord.gg/ku3jxx48Vh). Privacy policy and terms:
[gw2drops.com](https://gw2drops.com).

You must be 18 or older to create a gw2drops.com account.

## Legal

GW2Drops is an unofficial fan project, not affiliated with or endorsed by ArenaNet
or NCSOFT. Use third-party addons at your own risk.

© ArenaNet LLC. All rights reserved. NCSOFT, ArenaNet, Guild Wars, Guild Wars 2, GW2, Heart of Thorns, Path of Fire, End of Dragons, Secrets of the Obscure, Janthir Wilds, Visions of Eternity, and all associated logos, designs, and composite marks are trademarks or registered trademarks of NCSOFT Corporation. All other trademarks are the property of their respective owners.
