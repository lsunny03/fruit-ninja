# Fruit Ninja Game!

A single-page browser game. Slice fruit with a swipe or drag, avoid bombs, and keep your lives.

## Running it

Open `index.html` in a browser. There is no build step, server, or dependencies beyond the Google Fonts stylesheet loaded from a CDN.

## How to play

- Swipe or drag across falling fruit to slice it. Each slice splits the fruit and adds to your score.
- Quick slices in a row build a combo, which adds bonus points.
- Each fruit that falls off the bottom costs one of three lives.
- Slicing a bomb ends the game immediately. Bombs get more common the longer you play.

## Start menu options

- **Theme:** Classic, Sunset, Neon Night, or Jungle. Changes the background gradient and accent colors.
- **Mode:** Dark or Light. Light mode uses a pale sky background and dark text.
- **Fruit:** Choose which fruit types can spawn. START is disabled when none are selected.
- **Blade:** Choose the color of the slice trail, or pick Random to get a different color each game.

All of these choices are saved in the browser's `localStorage` and persist across visits. Your best score is also saved there.

## Files

- `index.html`: the entire game (markup, styles, and script).
- `README.md`: this file.

## Known limitations

- Layout and difficulty have not been tested on a range of screen sizes or devices.
- Scores and settings are per browser and are not shared across devices.
