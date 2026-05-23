<div align="center">

<br />

# ✦ Ellington Beach House

### _A waterfront residence on Palm Jumeirah — Apartment N-405_

<br />

![HTML5](https://img.shields.io/badge/HTML5-Semantic-C9A961?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Custom_Properties-8B6F3D?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-1A1715?style=flat-square&logo=javascript&logoColor=white)
![Reveal.js](https://img.shields.io/badge/Reveal.js-6-C9A961?style=flat-square&logo=reveal.js&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-Live-1A1715?style=flat-square&logo=netlify&logoColor=white)

<br />

> An editorial **property dossier** for a luxury Palm Jumeirah residence —
> built as a vertical-scroll presentation with hand-typeset spreads,
> bilingual EN / RU copy, and a sand-and-bronze palette inspired by
> high-end print magazines.

<br />

**🌐 Live demo:** [presentatinsdubai.netlify.app](https://presentatinsdubai.netlify.app/)

<br />

![Ellington Beach House](./ELLINGTON%20BEACH%20HOUSE/assets/elington.png)

</div>

---

## ✦ About the Project

**Ellington Beach House** is a private real-estate presentation designed to feel
like a printed luxury catalogue. Each section is a full-bleed editorial spread —
cover, hero, description, specifications, amenities, location, agent — that
flows in a single vertical scroll, the way a magazine reader turns pages.

The presentation is bilingual: every block carries both the English headline
and a discreet Russian translation, so the dossier serves international buyers
and Russian-speaking clients without two separate builds.

---

## 🌴 Features

- **Editorial layout** — magazine-grade typography with Cormorant Garamond display + Manrope UI
- **Bilingual content** — EN / RU side-by-side on every slide (Cyrillic handled via Montserrat override)
- **Sand · Champagne · Bronze · Charcoal** palette tuned for warm luxury
- **Vertical-scroll dossier** — cover, hero, description, specs, amenities, location, agent
- **Custom SVG icon set** — bath, bed, beach, palm, Burj Khalifa, visa, document, and more
- **Fully responsive** — desktop spreads gracefully reflow on tablet and mobile
- **CSS variables** — single source of truth for color, type scale, and spacing
- **Static & lightweight** — no build step, no framework runtime, instant load

---

## 📁 Project Structure

```
Presentation/
├── ELLINGTON BEACH HOUSE/         # The presentation itself
│   ├── assets/
│   │   ├── icons/                 # SVG icon set (bath, bed, beach, palm…)
│   │   ├── agent.jpg              # Agent portrait
│   │   ├── elington.png           # Hero atmosphere photo
│   │   ├── logo.png               # Top Address wordmark
│   │   └── logo-mark.png          # Top Address monogram
│   ├── css/
│   │   └── theme.css              # Design tokens + all slide styles
│   ├── index.html                 # Every editorial spread, in one document
│   └── package.json               # Local dev server config
├── icons/                         # Shared icon library
└── netlify.toml                   # Netlify publish config
```

---

## 🛠 Tools & Stack

| Layer            | Tool                                 | Purpose                          |
| ---------------- | ------------------------------------ | -------------------------------- |
| **Markup**       | HTML5                                | Semantic editorial spreads       |
| **Styling**      | CSS3 + Custom Properties             | Design tokens, layout, animation |
| **Typography**   | Google Fonts                         | Cormorant Garamond · Manrope · Montserrat (Cyrillic) |
| **Presentation** | Reveal.js 6                          | Slide framework foundation       |
| **Icons**        | Custom SVG set                       | Lightweight, sharp at any size   |
| **Dev server**   | http-server (via npx)                | Zero-config local preview        |
| **Hosting**      | Netlify                              | Continuous deploy from `main`    |
| **Version**      | Git + GitHub                         | Source control                   |
| **Editor**       | VS Code + Claude Code                | Authoring & iteration            |

---

## 🚀 Getting Started

**1. Clone the repo**

```bash
git clone https://github.com/KausarShangareeva/Presentation.git
cd Presentation/"ELLINGTON BEACH HOUSE"
```

**2. Install dependencies**

```bash
npm install
```

**3. Run the local dev server**

```bash
npm run dev
```

Open **http://localhost:8080** — the presentation opens straight on the cover spread.

> 💡 No build step. Edit `css/theme.css` or `index.html`, refresh, done.

---

## 🌐 Deploy to Netlify

The repo ships with a `netlify.toml` that tells Netlify exactly what to publish:

```toml
[build]
  publish = "ELLINGTON BEACH HOUSE"
```

1. Push the repo to GitHub
2. Go to [netlify.com](https://netlify.com) → **Add new site → Import from Git**
3. Select the repo — Netlify picks up `netlify.toml` automatically
4. Deploy. That's it.

Live build: **[presentatinsdubai.netlify.app](https://presentatinsdubai.netlify.app/)**

---

## 🎨 Color Palette

| Token             | Value                  | Usage                              |
| ----------------- | ---------------------- | ---------------------------------- |
| `--c-bone`        | `#FBF8F2`              | Page background, light spreads     |
| `--c-cream`       | `#F4EFE7`              | Secondary surfaces                 |
| `--c-sand`        | `#E8DFD0`              | Dividers, soft fills               |
| `--c-champagne`   | `#C9A961`              | Accents, gold rules, eyebrows      |
| `--c-bronze`      | `#8B6F3D`              | Secondary accent, hover states     |
| `--c-graphite`    | `#2D2926`              | Body text on light backgrounds     |
| `--c-ink`         | `#1A1715`              | Dark spreads, headings             |

---

## ✒️ Typography

| Family                  | Role                       |
| ----------------------- | -------------------------- |
| **Cormorant Garamond**  | Display headings, titles   |
| **Manrope**             | UI, body copy              |
| **Montserrat**          | Cyrillic glyph override    |

---

## 📐 Slide Index

1. **Cover** — brand lockup, edition mark, medallion
2. **Hero** — title spread with atmosphere photo
3. **Description** — three-column editorial spread about the residence
4. **Specifications** — area, layout, bedrooms, baths (sqft + sqm)
5. **Amenities** — beach, pools, restaurants, kindergarten
6. **Location** — Palm Jumeirah map + distances to landmarks
7. **Agent** — point of contact, Top Address Real Estate

---

<div align="center">

<br />

Crafted for **Top Address Real Estate** — Private Collection · 2026 🌊

</div>
