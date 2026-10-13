# Time Co ⏳

**Full-screen falling-sand timer** — the whole screen is the container. Geometric grains rain from above with sand-like physics and pile up; the screen fills exactly when the countdown ends. **Times Up.**

**[Live demo →](https://artzdesignmo.github.io/time-co/)**

## How it works

1. Pick a **grain form** — circle, square, triangle, diamond, hexagon
2. Pick a **duration** — 1 / 5 / 10 / 15 / 30 / 60 min or custom
3. Pick a **container** — full screen, glass vessel, or orb — and its size (S / M / L)
4. Pick a **color** — 6 palettes
5. Press **Start** — grains fall irregularly from above and stack until the screen is full

## During the run

- **Floating icon buttons** switch color and grain form mid-fall — new grains take the new style instantly
- **iPhone gyroscope**: tap the motion button, then tilt or shake your phone — the sand follows
- Pause / resume, auto-pause when the tab hides
- Procedural WebAudio chime at **Times Up**

## Details

- Hand-written Canvas 2D physics: gravity, velocity trails, pile heightfields, container clipping
- devicePixelRatio-sharp rendering, 60 fps
- EN / 中文 toggle (default EN), Dela Gothic One display type
- Light silver-gray / white / black themes (stage stays dark for contrast)
- Single `index.html`, zero dependencies, 100% offline

## Buy Me a Coffee

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-whynotartmoney-FFDD00?style=flat-square&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/whynotartmoney)

## License

MIT
