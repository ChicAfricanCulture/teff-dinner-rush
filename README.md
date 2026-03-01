# Teff Dinner Rush (Teff Texture Trap)

A minimal-asset, arcade-chaos “mind game” about teff textures—built as a single `index.html` file for an African food archive.

Play it here: https://chicafricanculture.github.io/teff-dinner-rush/

## What it is
**Teff Dinner Rush** disguises a texture lesson inside a fast, pressure-based game loop.

You’re making teff bread for family dinner. Texture tags fly in under chaos. Your job is to keep the batch stable and finish it in time—without the batch collapsing.

No images. No libraries. No build steps. Just one file.

## How to play
- **Drag** a floating texture tag (Whole / Cracked / Coarse / Fine / Batter)
- **Drop** it into the matching station at the bottom
- Correct drops **stabilize** the batch and fill **Batch Ready**
- Wrong drops spike **Instability**
- If **Instability hits 100** → batch collapses
- If the **Dinner ETA timer hits 0** → family arrives

### Win condition (the “why”)
Fill the **Batch Ready** bar to complete a batch.
Complete more batches before the timer ends to push your score higher.


## Controls
- Mouse: click + drag
- Touch: tap + drag

## Tech
- Single-file HTML + Canvas 2D
- Optional WebAudio (no external assets)
- High score saved in `localStorage`

## Run locally
Just open `index.html` in a browser.

## Credits
Created for the SankofaKitchen / ChicAfricanCulture archive to prove African food belongs in the game space too.
