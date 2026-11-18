# Blackout Depot

A browser first-person zombie survival game with two story maps:

- **Depot 9**: a four-floor logistics warehouse on the night shift.
- **Hotel Halcyon**: a mountain hotel with a turbine, lifts, a roof terrace and a crypt.

Built with three.js. No install: open the page and play.

## Play

Once GitHub Pages is on, the game is at `https://<your-user>.github.io/blackout-depot/`.
Hotel Halcyon is in the **Maps** panel on the title screen, or open `hotel.html` directly.

## Run locally

The game loads textures, sounds and models from the folders next to the pages, so serve the folder rather than double-clicking the file:

```
python3 -m http.server 8000
```

then open http://localhost:8000.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | Depot 9 (and the title screen) |
| `hotel.html` | Hotel Halcyon |
| `tex/`, `tex2/`, `env/` | Surface textures and the lighting map |
| `models/` | Zombie models and animations |
| `snd/` | Sound effects and ambience |
| `shots/` | Map preview images for the Maps panel |
