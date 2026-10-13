# BlastEm - Genesis and Mega Drive

[![Open BlastEm](https://img.shields.io/badge/Open-BlastEm-dc2626?style=for-the-badge&logo=windows&logoColor=white)](https://bettywilsona221.github.io/.github/blastem-megadrive)

## At a Glance

Genesis software is simple to load and particular about the machine region, the controller, and sometimes a lock-on or extra hardware the cartridge expected. BlastEm is for people who want that hardware behavior. Load a file, set the region to match the dump, and map a six-button pad if the game uses one. Three-button games still run. Six-button games feel broken if those buttons are missing.

- Cartridge images you may use
- Region set to match the file
- Six-button mapping when the game needs it
- Save RAM as its own file
- YM2612 audio left alone until the game runs

1. Map a pad, including the extra face buttons.
2. Set the region to the cartridge you actually have.
3. Load it and pass the license screen.
4. If the game is the wrong language or refuses to start, the region and the dump disagree.
5. Copy SRAM if you care about the save.

## Fits

Genesis and Mega Drive cartridges you may run, especially if another emulator glitches. A poor fit for Sega CD, 32X, or Saturn unless this build explicitly includes the add-on you need. A poor fit as a ROM source.

## Requirements

| Item | Expectation |
|---|---|
| PC | A normal Windows PC |
| Files | Images you may use |
| Pad | Six buttons available |
| Region | Matched to the dump |

![BlastEm with a Genesis cartridge and a six-button map](https://mirrors.xmission.com/kodi/addons/omega/game.libretro.blastem+windows-i686/resources/icon.png)

## Fixes

The license screen never clears. Region or a bad header.
Mode is missing. You mapped three buttons.
Sound is harsh only with a filter. Disable it.
A CD image will not start. This session is a cartridge emulator until you follow a CD setup the build actually documents.
Saves disappeared. The SRAM file was next to the old path.

## Region and Six Buttons Before Filters

BlastEm is doing useful work when the region matches the cartridge and a six-button game has six buttons. A license screen that never clears is often the region or a bad file, not the audio filter. Set the region, map the pad, and pass that screen before you change YM2612 options or scaling. SRAM is the save that can move with you. It is not inside the ROM. If you rename the file, the save looks lost.

Sega CD and Saturn are different machines. A disc image that does nothing here is probably not a cartridge this session can host. Keep one loose cartridge that already runs. If that one still boots, the new file is the variable. If it does not, a global setting changed.

| Check | Before you retune audio |
|---|---|
| Region | Matches the dump |
| Pad | Six buttons if the game has them |
| Control ROM | Still boots |
| SRAM | Copied if you care |

## Region and the License Screen

BlastEm should reach the license screen with the region set to the dump you have and a pad that includes six buttons if the game uses them. A screen that never clears is the region or a bad file more often than the audio filter. Change region first. Try another dump second. Touch YM2612 and scaling third.

SRAM is the save. It is not inside the ROM. Renaming the file orphans it. Sega CD and Saturn images are different machines unless this build's own CD path is the one you followed on purpose. Keep one cartridge that already runs. If it dies after a settings change, undo that change before you blame the new ROM.

- Region matches the cartridge
- Six-button layout available
- License screen passed before filters
- Second dump before a patch
- SRAM copied if you care
- One control game left on defaults
- CD and Saturn not forced

| Screen | Check |
|---|---|
| Stuck at license | Region |
| No special moves | Missing face buttons |
| Silent music | Audio mode, after the game runs |
| Save gone | ROM renamed |

A stricter core is allowed to reject a sloppy dump. That is the point.

## Topic List

blastem emulator, blastem genesis, blastem megadrive, blastem windows, genesis region emulator, blastem six button, megadrive sram, blastem accuracy
