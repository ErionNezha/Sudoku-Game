# Sudoku Game

Play it live: **https://erionnezha.github.io/Sudoku-Game/**

A classic 9×9 Sudoku game. This repo contains two versions of the same game:

## Original Python

`sudoku.py` — the original desktop game written in Python with **turtle graphics + tkinter**.
Run it with:

```bash
python sudoku.py
```

Requires `numpy` and `tkinter` (`pip install numpy`; tkinter ships with most Python installs).
It opens a royal-blue window titled "LET'S PLAY SUDOKU", generates a random solvable board,
and you play with mouse + keyboard (1–9 to fill, Delete to erase, arrows to move, Enter to check,
`r` to reset, space to reveal the answer, Esc to quit).

## Web version

`index.html` — the same game rewritten in plain HTML/CSS/JavaScript so it runs directly
in the browser (e.g. GitHub Pages). Single file, no dependencies, no CDN — just open it.

### Controls

- **Click / tap a cell** — selects it and highlights its row, column and 3×3 box
- **Type 1–9** (or tap the on-screen number pad) — fills the selected cell
- **Backspace / Delete** (or the ⌫ pad button) — erases the selected cell
- **Arrow keys** — move the selection
- **Enter** — checks the board
- **New Game** — loads a new puzzle (3 built-in, each verified with a unique solution)
- **Check** — verifies the board: wrong entries turn red, empty cells are outlined
- **Reset** — clears your entries and restores the original puzzle

Fill the whole grid correctly and you win. 🎉
