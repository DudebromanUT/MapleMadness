# MapleMadness

Game of Maple.

A phone game starring Maple the Welsh terrier and Fig the cat, set in Millcreek, Utah.

Four levels: Poop Patrol (endless turbo mode, gets harder every 20 seconds; if Mom or Dad steps in poop, game over; if Dad mows over one, it turns into four), Catch Fig, Garden Duty, and Tug of War. English and Spanish.

## Play

Open the GitHub Pages link in Safari, then Share → Add to Home Screen.

## Files

- `index.html` – the whole game (art, sound, levels, text)
- `apple-touch-icon.png` – home screen icon
- `manifest.webmanifest` – lets the phone open it full screen

## Easy edits in index.html

- Game text (English and Spanish): search for `Poop Patrol`
- Maple's colors, including the green collar: `MC = {`
- Poop Patrol difficulty: `turbo: 4` (Maple speed and poop rate), `stageLen: 20` and `lawnMax: 7`
