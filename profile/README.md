# melonDS - Nintendo DS and DSi Emulation

## At a Glance

The DS is two screens, a touch panel, and a set of firmware the games expect to find. melonDS gives you both screens, a way to click or map the touchscreen, and slots for the firmware files it needs. Once those files are in place, loading a cartridge image is the ordinary loop. DSi-mode titles need the DSi side of that firmware story, not only the original DS BIOS.

- DS and DSi emulation in active development
- Touchscreen via mouse or a mapped device
- Microphone and camera features where the build supports them
- Local wireless between instances when you configure it
- Firmware you supply; games you supply and may use

[![Open melonDS](https://img.shields.io/badge/Open-melonDS-2563eb?style=for-the-badge&logo=windows&logoColor=white)](https://mouron455.github.io/.github/melonds-dsi)

## Firmware

| File | Why it is required |
|---|---|
| DS BIOS and firmware | The original handheld boot path many games expect |
| DSi BIOS and NAND-related files | DSi mode and DSi-only software |
| SD or NAND contents | Where DSi software expects storage |
| Nothing from a random pack | A mismatched firmware looks like a broken emulator |

Keep firmware next to the emulator in a folder you named, and do not mix DS and DSi files in one unlabeled directory. melonDS will not ship those commercial files for you. Dump them from hardware you own or otherwise obtain them only if you may.

## Screens and Touch

The default layout shows both panels. Rotate or stack them to match how you want to look at the machine, not how a screenshot online was cropped. Touch controls need a device that can click the lower screen; a controller mapping can send buttons, and the mouse can stand in for the stylus. If a game asks you to draw and the clicks land on the wrong panel, fix the layout before you call the game broken.

Microphone input matters for a handful of titles. Leave it unset until a game actually asks. Camera features are similar: configure them when the software wants a photo, not on the first boot.

## Steps

1. Install melonDS and read which firmware the version expects.
2. Add DS firmware you may use, then boot to the firmware screen once.
3. Add DSi files only if you need DSi mode.
4. Map buttons and test the touchscreen on the lower panel.
5. Load one cartridge image and pass the title screen.
6. Add local wireless only after single-player play is already fine.

## Requirements

| Item | Minimum | Recommended |
|---|---|---|
| OS | 64-bit Windows the build supports | Current Windows |
| CPU | A recent dual or quad core | More headroom for DSi and upscaling |
| RAM | Modest | Modest |
| Disk | Emulator plus firmware and saves | Saves backed up separately |
| Input | Keyboard and mouse | A controller plus mouse for stylus games |

## Fits

DS and DSi software you have the right to run, including titles that need the touchscreen to be honest. A poor fit for 3DS games. A poor fit for a machine that cannot keep full speed; emulation that drops frames makes rhythm and microphone titles worse, not nostalgic. A poor fit as a download store. The emulator is empty until you bring firmware and games.

![melonDS dual screen layout with firmware already configured](https://upload.wikimedia.org/wikipedia/commons/4/44/MelonDS_Logo.png)

## Fixes

Boot stops immediately. Firmware files are missing or swapped between DS and DSi.
The game runs and the stylus misses. You are clicking the upper screen or the layout scaled the touch region.
DSi software will not start. You are still in DS mode or the NAND path is wrong.
Saves do not stick. The emulator cannot write its folder. Move it out of a protected directory.
Local wireless does not see the other window. Get one game running locally before you debug a second instance.

## Firmware Stays Named

Keep DS and DSi files in separate folders with the chip name in the filename. A later update of melonDS should point at those same paths rather than at a fresh download of unclear origin. Saves are not inside the cartridge image. Copy the save directory before you delete a portable folder you used for a test.

Local wireless is a second project. One game that boots and accepts the stylus is the first project. If that game is slow, fix speed before you open a second window.

| File | Keep it |
|---|---|
| Named firmware | Yes, if you may use it |
| Save folder | Yes, copied with the games |
| A second instance | Only after one game is fine |

## Topic List

melonds, melonds emulator, melonds dsi, melonds firmware, nintendo ds emulator windows, melonds touchscreen, dsi nand melon, melonds local wireless
