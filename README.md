<div align="center">

# Mario Kart Nitro: Nitropack

**The mod files for Mario Kart Nitro.**
Custom tracks, characters, music and more for Mario Kart Wii.

[![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](LICENSE)
[![Launcher](https://img.shields.io/badge/Launcher-mkwiichannel%2Fnitro-ff8c00.svg)](https://github.com/mkwiichannel/nitro)
[![Discord](https://img.shields.io/badge/Discord-Join-5865F2.svg)](https://discord.gg/AhkHNPG65G)

</div>

---

## Just want to play?

You don't need to download anything from this page. Get the
**[Mario Kart Nitro launcher](https://github.com/mkwiichannel/nitro/releases/latest)**.
It downloads this pack for you, keeps it up to date, and starts the game in Dolphin.

This repository is the data the launcher reads from. It is about 1.6 GB, so
please don't clone it by hand unless you want to look inside.

## What's inside

| Folder | What it holds |
|---|---|
| `MarioKartNitro_Test/Tracks` | Custom track files |
| `MarioKartNitro_Test/Characters` | Characters, karts and bikes, with their variants |
| `MarioKartNitro_Test/CTBRSTM` and `sound` | Custom music and sound |
| `MarioKartNitro_Test/Assets`, `MenuRace`, `Scene`, `Model` | Menus, race screens and other game assets |
| `MarioKartNitro_Test/Binaries` | The code and config files the mod loads |
| `riivolution` | The Riivolution patch (`MarioKartNitro.xml`) and its config |
| `MKNitroFont` | The custom font |

## Riivolution options

The patch gives you two options in Riivolution's menu. The launcher sets them for you.

- **Mario Kart Nitro:** enables the mod.
- **My Stuff:** `Disabled`, `Enabled`, or `Music Only`. This lets you add your own
  files, like music, on top of the pack.

The mod uses its own license save, so it doesn't touch your normal Mario Kart Wii
save. Your current save is copied over the first time you play.

## How it's used

The launcher reads this repo from GitHub and only downloads files that changed.
Every file is checked against its hash, and an interrupted download continues
where it stopped. The files are then placed in Dolphin's `Load/Riivolution` folder.

## License

GPL v3, see [LICENSE](LICENSE).

## Community

Questions, bugs, or just want to chat? Come to the
[Discord](https://discord.gg/AhkHNPG65G).

---


