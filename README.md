# Rookie to Legend

This project is a single-file MLB career simulator inspired by GOAT Lab-style build systems, but built for a browser and tuned for a lighter, fast-play experience with real-player-based attributes.

## Features
- Hitter and pitcher modes
- Real MLB player pool from multiple eras
- RPG-style attribute build system with weighted overall calculation
- Spin/build phase with card assignments
- Career progression with seasonal stat outputs and veteran verdicts
- Hall of Fame / legacy style end result

## Run locally
1. Open `index.html` directly in a browser, or
2. Serve the folder with a simple local server:
   ```bash
   python -m http.server 8000
   ```
3. Visit `http://localhost:8000`.

## Files
- `index.html` — Full simulator UI and logic
- `hitters.csv` — Extended historical hitter pool
- `pitchers.csv` — Extended historical pitcher pool

## Notes
The simulator is intentionally compact enough to run in a single static file while still using real MLB names and a deeper attribute system inspired by the design doc you provided.
