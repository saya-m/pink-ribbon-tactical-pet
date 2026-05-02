# Setup

## Install Into Codex

1. Create a local folder for the pet, for example:

   - `<CODEX_HOME>/pets/pink-ribbon-tactical-pet/`

2. Copy:

   - `assets/spritesheet.webp` -> `<CODEX_HOME>/pets/pink-ribbon-tactical-pet/spritesheet.webp`
   - `pet/pet-config.json` -> `<CODEX_HOME>/pets/pink-ribbon-tactical-pet/pet.json`

3. Restart Codex or reload the custom pet list.
4. After installation, select `Pink Ribbon Agent` from your custom pets list in Codex.

## Expected Final Layout

```text
<CODEX_HOME>/pets/pink-ribbon-tactical-pet/
  pet.json
  spritesheet.webp
```

## Notes

- `spritesheet.png` is included for inspection and documentation, not as the runtime asset.
- `contact-sheet.png` is a QA artifact and is optional for installation.

## Troubleshooting

- If the pet does not appear, verify that the final filenames are exactly `pet.json` and `spritesheet.webp`.
- If Codex still shows an old version, restart the app after replacing the files.
