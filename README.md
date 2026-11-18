# Name Search Game

A crossword-style word search built from your own list of names, with an occasion heading on top.

## Run
Open `index.html` in a browser, or serve it locally:

```
python3 -m http.server 8765
```

Then go to http://localhost:8765.

## Features
- Occasion heading and optional subheading
- Add names by typing, pasting, or uploading a `.txt`/`.csv` file (see `sample-names.csv`)
- Easy / Medium / Hard difficulty (across+down, diagonals, backwards)
- Drag to select names; found names are coloured and crossed off
- Timer, hints, reveal all, new grid
- **Download PDF / Print** in A1, A2, A3, A4, A5 or A6, portrait or landscape, with an optional answer key page (vector, so it stays sharp at poster size)
- **Download game (HTML)**: saves a single offline file pre-filled with your heading and names, which opens straight into the puzzle
- Settings saved in the browser (localStorage)
