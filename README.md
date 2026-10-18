# Angie's Games

Two hand-built browser games, no frameworks, no build step — just open and play.

**Play online:** https://angie4448.github.io/angie-games/

---

## 🏔 Machu Picchu

An open-world exploration of the Inca citadel, in the visual language of a certain
open-air adventure game.

- Procedural terrain built from real geography: a 3 km ridge with the citadel's saddle
  at 2 431 m, Huayna Picchu at 2 720 m, and the Urubamba river cutting a 670 m gorge below
- Agricultural terraces generated as constant-width steps, with retaining walls that
  line up with the terrain to the centimetre
- Day/night cycle, six weather states, a sea of cloud in the valley
- Climbing, paragliding, stamina, landmarks, a passport, and a photo mode
- Touch controls; plays in landscape on a phone

`machu-picchu/index.html` — one self-contained file, three.js r149 inlined.

## 🎓 Fudan PhD Simulator

Four years, 48 months, five fields. Pick a journal — *Nature*, *Science*, *Cell*,
a CSSCI title — and every manuscript you send out comes back **accepted**.

- Monthly action points: read, run experiments, write, meet your supervisor
- Paper titles, reviewer reports and campus news are all generated
- CV, citations, h-index, and four possible endings after the defence

`fudan-phd/index.html` — one self-contained file, no dependencies.

---

## Run locally

```bash
git clone https://github.com/Angie4448/angie-games.git
cd angie-games
python -m http.server 8000
# then open http://localhost:8000
```

Both games work from `file://` too — just double-click the HTML file.

## Credits

- [three.js](https://threejs.org) (MIT) — inlined into the Machu Picchu build
- All textures, geometry, audio and music are generated at runtime. No external assets.
