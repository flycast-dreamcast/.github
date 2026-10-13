# Flycast - Dreamcast and Naomi

## At a Glance

Dreamcast software arrives as disc images. Arcade Naomi software arrives as board dumps with their own file layout. Flycast can host both, which is convenient and also how people mix up a GD-ROM image with an arcade ZIP and call the emulator broken. Pick the system, then pick a file that belongs to that system.

- Dreamcast disc images and Naomi arcade sets
- Upscaling and widescreen options after the game already runs
- Controller mapping, including VMU-style save behavior where it applies
- BIOS files only when required, supplied by you
- A desktop build that expects a normal GPU driver

Rendering upgrades are optional. A game that crashes at the title screen will not be saved by a higher internal resolution. Boot it at a plain setting, then raise resolution if the host keeps up.

## Images and BIOS

| Content | What Flycast expects |
|---|---|
| Dreamcast game | A disc image you may use, in a format the build reads |
| Naomi or similar arcade | The ROM set the version of Flycast documents, if you may use it |
| BIOS | Only if that system path asks, from a dump you may use |
| Saves | A folder you can back up, separate from the disc image |

A cue/bin or other image that does not match the dump will hang on the boot logo. Replacing it with a random download is not troubleshooting. Verify the image you already have the right to use, or stop. Flycast is not a loader for loose video files and it is not a substitute for owning the disc.

## Picture and Input

Dreamcast controllers and arcade panels are different maps. Configure the one you are actually playing. Analog sticks on a modern pad can be assigned to the Dreamcast stick; do that before you decide a racing game feels wrong. VMU saves and memory cards are easy to forget until a game tells you the card is missing. Create the card file in the emulator once and keep it.

Widescreen and higher resolution change the picture and can change performance. Apply them per game if a title's interface breaks under a hack, and leave them global only when you like the result on everything you play.

## Steps

1. Install Flycast and set the BIOS path only if your system needs it.
2. Map a controller for Dreamcast, not for a different Sega console.
3. Load one disc image and reach the title screen at default resolution.
4. Create a VMU or save file if the game asks for a memory card.
5. Raise internal resolution after the game is stable.
6. Treat Naomi sets as a separate library with their own files.

## Requirements

| Item | Minimum | Recommended |
|---|---|---|
| OS | 64-bit Windows the release supports | Current Windows |
| CPU | A modern quad-core | Headroom for upscaling |
| GPU | A GPU with current drivers | Required for higher internal resolutions |
| RAM | Ordinary | Ordinary |
| Disk | Images and save files | Saves backed up apart from disc images |

[![Open Flycast](https://img.shields.io/badge/Open-Flycast-0f766e?style=for-the-badge&logo=windows&logoColor=white)](https://bringer1992cromer.github.io/.github/flycast-dreamcast)

## Fits

Dreamcast discs and supported arcade boards you may run. A poor fit for Saturn, Genesis, or model-2 arcade hardware. A poor fit on a PC whose GPU driver is broken; update the driver before you collect emulator settings. A poor fit as a source of games. The window stays empty until you point it at an image.

## Fixes

Boot hangs on the logo. The image is incomplete or the BIOS requirement was ignored.
Naomi will not start. The set's files do not match what this Flycast version expects, or files are missing.
The picture is a smear. Disable widescreen hacks and lower the internal resolution.
Saves vanish. The VMU file was never created, or you launched a different instance with a different folder.
Audio stutters only when upscaled. Drop the render scale before you change audio buffers.

## One System at a Time

A Dreamcast disc that reaches the title screen is your control. Naomi sets are a different library and should not be judged by that disc. When a new image fails, boot the control disc before you change BIOS or renderer. Upscaling stays off until the control disc is stable, then rises one step.

VMU files and arcade saves live outside the disc image. Copy them when you move Flycast. Replacing a disc image does not keep the save.

| Library | Do not mix with |
|---|---|
| Dreamcast discs | Naomi sets |
| A working control disc | A new renderer and a new BIOS on the same boot |
| VMU file | The disc image itself |

## Term Index

flycast emulator, flycast dreamcast, flycast naomi, flycast windows, dreamcast disc image, flycast vmu save, flycast upscale, naomi rom set flycast
