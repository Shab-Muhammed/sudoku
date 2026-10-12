# Gridwise Sudoku

A responsive browser-based Sudoku game with four difficulty levels, progression rewards, daily streaks, and unlockable themes. Built with plain HTML, CSS, and JavaScript.

## Play locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

No build step or package installation is required. The game loads [canvas-confetti](https://www.npmjs.com/package/canvas-confetti) from jsDelivr for the victory celebration and Google Fonts for typography, so those enhancements need an internet connection. Gameplay itself runs in the browser.

## Features

- Randomized Sudoku puzzles with a unique solution: Easy, Medium, Hard, and Expert.
- Touch-friendly number pad, keyboard navigation, pencil notes, undo, erase, hints, pause, timer, and move counter.
- Optional live error checking and three-mistake limit.
- XP, ten player levels, coins, daily login streak rewards, and a theme store.
- Six visual themes, including the Day 7 Golden Master reward.
- Victory summary with time, precision, XP and coins earned, plus a canvas-confetti particle burst.
- Progress, unlocked themes, and player stats saved locally in the browser using `localStorage`.
- Responsive layout for desktop, tablet, and mobile screens.

## Files

- `index.html` — page structure and CDN script references.
- `styles.css` — interface styling, themes, and responsive breakpoints.
- `game.js` — Sudoku generation, gameplay, rewards, and persistence.

## Persistence

The game stores its profile in the browser under the `gridwise-save-v1` localStorage key. Progress is tied to the browser and device where it was earned. Clearing browser site data will remove that local save.

## License

Add a license before distributing this project if you want to specify reuse terms.
