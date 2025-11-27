# Tic Tac Toe

Simple browser-based Tic-Tac-Toe game.

## Files
- [index.html](index.html) — main HTML file that loads the game.
- [style.css](style.css) — styles for the board and UI.
- [app.js](app.js) — game logic and event handlers.

## Features
- Two-player local play (O and X alternate turns).
- Win detection using the [`winPatterns`](app.js) array.
- Winner display via [`showWinner`](app.js).
- Draw detection after 9 moves.
- Reset/new game using [`resetGame`](app.js), [`enableBoxes`](app.js) and [`disableBoxes`](app.js).

## How to run
1. Open [index.html](index.html) in a browser (double-click or use browser "Open File").
2. Or serve the folder and open http://localhost:8000:
   ```sh
   python -m http.server 8000
   ```

## Controls
- Click an empty square to place O or X.
- "Reset Game" / "New Game" buttons call [`resetGame`](app.js) to clear the board.

## Notes / Known issues
- Current implementation alternates starting player based on `turnO` default (initially O).
- Buttons are disabled after being clicked to prevent multiple marks in the same cell.

## Useful symbols (in app.js)
- [`winPatterns`](app.js)
- [`checkWinner`](app.js)
- [`showWinner`](app.js)
- [`resetGame`](app.js)
- [`enableBoxes`](app.js)
- [`disableBoxes`](app.js)

Enjoy!
