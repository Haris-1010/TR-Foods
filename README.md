# TR FOODS — website

Static website for TR FOODS (Spice is Life · King of Spice · Tayyab Rafiq · 0306 6103596).

## What's inside
- `index.html` — the whole site (HTML, CSS and JavaScript in one file)
- `logo.jpg`, `logo-180.jpg`, `favicon.png` — logo files
- `assets/js/three.min.js` — Three.js r128 (MIT) for the 3D hero
- `assets/fonts/` — Cinzel, Poppins, Noto Nastaliq Urdu (Open Font License), self-hosted

Everything is local — no CDN or Google Fonts needed.

## Features
- 3D hero: floating peppercorns, chillies, cardamom, coriander and star anise around spinning gold rings, following the mouse
- 3D tilting logo badge, 3D flip product cards, rotating 3D cube, tilt-on-hover feature and order cards, scroll-in animations
- Urdu (right-to-left, Nastaliq) and English — switch with one button; choice is remembered
- **Order sheet** (your original sheet, same 52 items, same rates and calculation):
  rates per dozen for 20 g / 50 g, per bottle for 250 ml / 500 ml / 1000 ml, live totals while typing,
  item search, add / edit / delete orders, grand summary, print, and **send any order on WhatsApp** to 0306 6103596.
  Orders and rates are saved in the browser (same storage keys as the old sheet, so old saved orders still appear).
- Phone and WhatsApp buttons, mobile menu, works on phones and tablets, respects "reduce motion"

## Put it online (free)
- **Netlify Drop:** go to app.netlify.com/drop and drag this folder in.
- **GitHub Pages:** upload the folder to a repository → Settings → Pages.
- Or open `index.html` directly from your computer.

## Edit
- Phone / WhatsApp: search `923066103596` and `0306 6103596` in `index.html`.
- Texts: the `T` object near the top of the `<script>` (each entry is `[Urdu, English]`).
- Featured products: the `PRODUCTS` list. Order-sheet items: the `items` list (and `EN_NAMES` in the same order).
