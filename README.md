# Chess Game

A browser chess game built with HTML, CSS, and JavaScript.

## Features

- 8x8 board generated with JavaScript
- OOP piece classes
- Legal move checking
- Check, checkmate, and stalemate detection
- Illegal move prevention
- Turn tracking
- Move history
- Captured pieces
- Restart button
- Legal move highlights
- Drag and drop support

## Run

Open `index.html` in a browser.

If you want to use a local server:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Test

```powershell
npm test
```

## Project Structure

```text
chess game/
|-- index.html
|-- package.json
|-- README.md
|-- docs/
|   `-- screenshots/
|-- scripts/
|   `-- capture_screenshots.ps1
|-- styles/
|   `-- main.css
`-- src/
    |-- main.js
    `-- modules/
        |-- board.js
        |-- chess-game.js
        |-- chess-ui.js
        |-- demo-scenarios.js
        `-- pieces.js
`-- tests/
    `-- chess.test.js
```

## Controls

- Click a piece to see legal moves
- Click a highlighted square to move
- Or drag a piece to a legal square
- Use restart to reset the match

## Screenshots

Screenshots are saved in `docs/screenshots/`.

- `01_start.png`
- `02_opening.png`
- `03_history.png`
- `04_check.png`

To generate them:

```powershell
.\scripts\capture_screenshots.ps1
```
