# Time Co ⏳

**Full-screen falling-sand timer** — pick a glass container, sand rains from above through its open top, walls block and pile the grains like a real glass. The container fills exactly when the countdown ends. **Times Up.**

**[Live demo →](https://artzdesignmo.github.io/time-mo/)**

## How it works

1. Pick a **grain form** — circle, square, triangle, diamond, hexagon
2. Pick a **duration** — 1 / 5 / 10 / 15 / 30 / 60 min or custom
3. Pick a **container** — full screen, cup, bowl, or **custom** (drag the dots to reshape your own vessel; + / − to add or remove points; the dashed edge is the opening)
4. Pick a **size** (S / M / L) and **color** — 6 palettes
5. Press **Start** — grains fall through the opening and stack until the glass is full

## During the run

- **Floating icon buttons** switch color and grain form mid-fall
- **iPhone gyroscope**: tap the motion button — tilt to pour the pile, shake to tumble the settled sand; it re-settles naturally
- Rotate your phone mid-run: the sand repacks and falls from the new top
- Pause / resume, auto-pause when the tab hides
- Procedural WebAudio chime at **Times Up**

## Details

- Hand-written Canvas 2D particle physics: wall collision, grain-to-grain stacking via spatial hash, substeps, velocity trails
- Pre-rendered grain sprites, devicePixelRatio-sharp, 60 fps
- EN / 中文 toggle (default EN), Dela Gothic One display type
- Light silver-gray / white / black themes (stage stays dark for contrast)
- Single `index.html`, zero dependencies, 100% offline

## Buy Me a Coffee

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-whynotartmoney-FFDD00?style=flat-square&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/whynotartmoney)

## License

MIT
