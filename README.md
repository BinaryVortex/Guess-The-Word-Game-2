# Guess-The-Word-Game-2

Guess-The-Word-Game-2 is a lightweight, browser-based word-guessing game built with plain HTML, CSS and JavaScript. It's a fun, mobile-friendly take on classic word-guess puzzles — open index.html in your browser and start guessing!

![Game Screenshot](./Screenshot%202024-09-07%20215029.png)

## Features

- Clean, responsive UI that works on desktop and mobile
- On-screen keyboard for easy play on touch devices
- Dynamic hint system (click "Show Hint")
- Adjustable difficulty (number of guesses scales with word length)
- Single-file, zero-dependencies (just open index.html)

## How to play

1. Open `index.html` in your browser.
2. A hidden word will be chosen at random.
3. Use the on-screen keyboard (or your physical keyboard) to guess letters.
4. Correct letters reveal their positions. Incorrect letters increase the mistake count and decrease remaining guesses.
5. Click "Show Hint" to reveal the hint for the current word.
6. Click "Reset Game" to start a new random word at any time.

## Run locally

1. Clone or download this repository.
2. Open the `index.html` file in any modern browser (Chrome, Firefox, Edge, Safari).

No build tools or server required.

## Customize

- Word list and hints are defined inside `index.html` (the `wordList` array). Edit or extend that array to add/remove words and hints.
- UI styles are inlined in `index.html` for convenience — feel free to extract them into a separate CSS file and tweak colors, fonts, and spacing.

## Files

- `index.html` — the full game (HTML, CSS, and JavaScript)
- `Screenshot 2024-09-07 215029.png` — screenshot used in this README
- `5331570.jpg` — background image used by the game

## Contributing

Contributions are welcome. Open an issue or submit a PR with improvements (new words, UI tweaks, accessibility fixes, etc.).

## Notes

- This project currently does not include an explicit license file. Add a LICENSE if you want to specify usage and attribution terms.

---

Happy hacking — have fun guessing!
