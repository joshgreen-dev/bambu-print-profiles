# bambu-print-profiles

A few filament profiles I've tuned for my P1S. Nothing revolutionary, just the settings that
actually work for me after a lot of wasted prints.

---

## Profiles

### PETG - Transparent (Bambu PETG Basic)
Standard profile doesn't handle transparency well at all. This slows down the outer walls
and drops temps slightly for cleaner layer lines.

`PETG_transparent.json`

### TPU 95A - Flexible Parts
The built-in TPU profile is too fast. This drops everything to sane speeds for small flex parts
like cable clips and gaskets.

`TPU_95A_slow.json`

### PLA - Fine Detail (0.2mm layer, 0.4 nozzle)
For anything that needs decent surface quality without going to 0.12. Good middle ground.

`PLA_fine_detail.json`

---

## Usage

Import via **Bambu Studio → File → Import → Import Config**.

---

## Notes

These are tuned for my specific P1S setup — AMS with dry box, build plate textured PEI.
Mostly using Prusament and Das Filament (easy to get in Europe). Your results may vary. Calibrate first.

If a profile is broken or off, open an issue. I update these when I revisit a filament.
