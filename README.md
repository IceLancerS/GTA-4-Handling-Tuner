# GTA 4 Handling Tuner

A simple browser tool for tweaking GTA IV's `handling.dat`. No install, no Python, no setup.

## 👉 Use it here: https://icelancers.github.io/GTA-4-Handling-Tuner/

## How to use

1. **Back up your original `handling.dat`.** Always keep a copy.
2. Open the link above.
3. Drop your `handling.dat` onto the page (or click to choose it).
4. Adjust the car and bike settings, or leave the defaults.
5. Click **Convert & download** to get `handling_modified.dat`.
6. Rename it to `handling.dat` and replace the original in your game files.

Grand Theft Auto IV\common\data\handling.dat
Grand Theft Auto IV\TBoGT\common\data\handling.dat
Grand Theft Auto IV\TLAD\common\data\handling.dat

Your file never leaves your computer. Everything runs locally in your browser.

## What it changes

**Cars**
- Centre of mass (Z) shift
- Brake bias
- Traction multiplier
- Suspension force and damping multipliers
- Suspension upper/lower limits

**Bikes / bicycles**
- Centre of mass (Z) shift
- Optional brake bias
- Traction multiplier
- Suspension force and damping multipliers
- Optional lean (COM) multiplier for the bike `!` lines

Bike settings are deliberately gentle by default. To leave bikes completely untouched, set the shifts to `0` and the multipliers to `1.00`.

## What it leaves alone

Boats, planes, helicopters and trains (including the cable car and subway) are never modified. Comments and all other lines in the file are kept as they are.

## Notes

- Handling is tuned by feel, so test in-game and adjust the values to taste.
- Default values are a starting point, not a perfect setup for every vehicle.
- Works in any modern browser (Chrome, Edge, Firefox, Safari). If the download doesn't start, open the page directly in the browser rather than inside a preview pane.

## Credits

Built with Claude (Anthropic).
