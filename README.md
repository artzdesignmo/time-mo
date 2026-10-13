# Time Mo ⏳

**Falling-sand countdown timer** — time rendered as falling sand. Sand drops as seconds pass; when the pile is full, time is up.

A web reimagining of [`whynotartmoney/Time-Art`](https://github.com/whynotartmoney/Time-Art) (an ESP32 falling-sand countdown), rebuilt for the browser with richer physics and a high-end flat design.

**[Live demo →](https://artzdesignmo.github.io/time-mo/)**

## Modes

- **Shape** — sand falls into a geometric form (circle, square, triangle, diamond, hexagon, rect)
- **Letter** — sand spells your words (up to 8 characters)
- **Pomodoro** — focus timer; the pile grows as you work (10 / 20 / 30 min presets + custom)
- **Stopwatch** — count up while the sand keeps falling

## Materials & colors

5 materials with distinct falling physics — **Fire** (fast, flickering), **Water** (slow, swaying), **Stone** (heavy, straight), **Gold** (sparkling), **Wood** (gentle spin) — across 6 color palettes (Gold, Ember, Leaf, Ocean, Violet, Rose).

## Details

- Hand-written Canvas 2D physics: gravity acceleration, velocity stretch, landing dust, pile heightfields, target-point settling for shapes & letters
- Procedural WebAudio completion chime
- Pause / resume / reset, auto-pause when the tab hides
- EN / 中文 toggle (default EN), Dela Gothic One display type
- Light silver-gray / white / black themes
- Single `index.html`, zero dependencies, 100% offline

## Buy Me a Coffee

If Time Mo helps your focus sessions, consider supporting:

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-whynotartmoney-FFDD00?style=flat-square&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/whynotartmoney)

## License

MIT
