# Ymir - Sega Saturn Discs and a BIOS You Provide

## Boot the Firmware First

Saturn software expects the console's own BIOS and then a disc. Ymir does not ship Sega's BIOS. Put a dump you may use in the slot the build names, and start once before you care about a game. You should see the Saturn's own boot behavior. If you do not, stop and fix the BIOS path. Loading more disc images will not create firmware.

Disc images need every track the cue file names, in the same folder. A single renamed video file is not a Saturn disc. Region should match the BIOS and the disc. A RAM cart or similar option is for titles that ask for it, not a global switch you leave on for the whole library.

## Pieces

| Piece | Rule |
|---|---|
| BIOS | Required, from a dump you may use |
| Cue and tracks | Kept together |
| Region | BIOS and disc should agree |
| RAM cart | Only the games that ask |
| Saves | Files you copy before you delete a build folder |

## Steps

1. Set the BIOS and reach the console's boot.  
2. Map the pad, including shoulders.  
3. Mount one disc whose cue resolves.  
4. Enable a cart only if that game asks, then reset.  
5. Raise any rendering option after the game is past the logo.  
6. Keep one working disc as a control for the next image.  

[![Open Ymir](https://img.shields.io/badge/Open-Ymir-4c1d95?style=for-the-badge&logo=windows&logoColor=white)](https://h65954047.github.io/.github/ymir-emulator)

## Fits

Saturn discs you may play, on a current Saturn emulator, with legal firmware. A poor fit for Kronos folder habits copied blindly. Read Ymir's own paths. A poor fit for other Sega generations. A poor fit if the cue points at tracks that are not there.

## Requirements

| Item | Expectation |
|---|---|
| PC | A current CPU and GPU drivers |
| BIOS | A file you may use |
| Discs | Images with tracks |
| Saves | Backed up with the config |

## Fixes

No BIOS screen. The file is missing, wrong region, or the wrong console.  
The disc is rejected. Fix the cue paths.  
One game asks for a cart. Set it for that game and reset.  
The control disc works and a new one does not. The new image is the problem.  
Video breaks after a driver update. Try the other renderer before you replace the BIOS.

![Ymir Saturn boot with a BIOS path set](https://play-lh.googleusercontent.com/gcxExFQFB0h9IzmJV1Nofv8YVAFDF6Zvt2zYKRYoyDLXbIrhqtwfXPRTs73mRbplP7bnPflH4eE3q08ZPv7f=w526-h296-rw)

## A Control Disc for the Next Image

Keep one Saturn disc that already reaches gameplay and do not retune it. When a new cue fails, boot that disc. If it still reaches the BIOS, the new tracks or the cue paths are wrong. If the control disc also dies, you changed BIOS, region, or renderer. Cart options stay on the games that ask for them. A global cart left on from one title confuses the next.

Saves live in the emulator folder. Copy them before you replace a portable build. Genesis and Dreamcast images will not boot here and should not be used as tests. Kronos settings are not Ymir settings. Read this build's paths when you move a folder.

| New disc fails | Control disc |
|---|---|
| Control still runs | Fix the new cue |
| Control also fails | Undo BIOS or renderer |
| Game asks for a cart | That title only |
| No BIOS screen | Firmware file, not the disc |

Cue files break when the tracks are renamed or moved without them. If the control disc still boots and the new one does not, open the cue in a text editor and see whether every track name is a file in that same folder.

## Phrase Index

ymir emulator, ymir sega saturn, ymir bios, ymir windows, saturn cue tracks, ymir ram cart, sega saturn emulator ymir, ymir save folder
