# Pink Ribbon Tactical Pet

<img src="assets/preview.gif" alt="Pink Ribbon Agent preview" width="360">

Unofficial fan-made Codex terminal pet package.

This project packages a small pink-ribbon tactical chibi companion designed for Codex-style terminal pet use.

## Important Notice

- This is an unofficial fan project.
- This project is not affiliated with, endorsed by, or associated with Capcom or the Resident Evil series.
- Character inspiration belongs to its respective rights holders.
- This package is shared for personal, non-commercial use only.

## What Is Included

- `assets/spritesheet.png`: readable atlas export for inspection
- `assets/spritesheet.webp`: install-ready spritesheet asset
- `assets/contact-sheet.png`: QA overview of the final animation rows
- `assets/preview.gif`: quick animation preview
- `pet/pet-config.json`: minimal Codex pet config
- `docs/setup.md`: installation steps
- `examples/preview.md`: asset preview page

## Install

1. Create a pet folder in your local Codex pets directory.
   Install under `<CODEX_HOME>/pets/pink-ribbon-tactical-pet/`.
2. Copy `assets/spritesheet.webp` into that folder as `spritesheet.webp`.
3. Copy `pet/pet-config.json` into that folder as `pet.json`.
4. Restart Codex or refresh the pet list.

Detailed notes are in [docs/setup.md](docs/setup.md).

## How To Use

After installation, select the installed custom pet from your custom pets list in Codex.
This pet appears in Codex as `Pink Ribbon Agent`.

## Animation States

- `idle`
- `running-right`
- `running-left`
- `waving`
- `jumping`
- `failed`
- `waiting`
- `running`
- `review`

## Asset Notes

- `spritesheet.webp` is the install target.
- `spritesheet.png` is included as an easier inspection asset.

## Source Positioning

This package was separated from a personal local workspace and prepared as a standalone distribution copy. It should not be presented as an official game asset pack or official Codex pet release.
