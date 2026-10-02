# Project Portfolio — Dicky Asqaeliany Ibnul Hakim

A static, build-free portfolio website showcasing my projects. Single-page landing (`index.html`) with dedicated detail pages for each project. Written in plain HTML + CSS (no frameworks, no bundler) with responsive layouts and automatic light/dark mode via `prefers-color-scheme`.

## Pages

| Page | File | Description |
|---|---|---|
| Home | [`index.html`](index.html) | Dark landing page with a 2×2 project card grid |
| AbsensiPro | [`project/…_Absensipro.html`](project/DickyAsqaelianyIbnulHakim_Portofolio_Absensipro.html) | AI-powered face recognition attendance system |
| ECOTRA | [`project/…_Ecotra.html`](project/DickyAsqaelianyIbnulHakim_Portofolio_Ecotra.html) | AI + IoT precision farming for chili cultivation (PKM-KC) |
| IoT Mini Smart Home | [`project/…_SmartHome.html`](project/DickyAsqaelianyIbnulHakim_Portofolio_SmartHome.html) | NodeMCU-based smart home prototype for SMAN 2 Bekasi |
| KRTI 2026 | [`project/…_KRTI.html`](project/DickyAsqaelianyIbnulHakim_Portofolio_KRTI.html) | National drone competition — Best Prototype award |

Every project page shares the same structure: header, hero mockup + meta table, tech stack strip, four write-up sections (Challenge / What I built / Impact / What I learned), photo showcases, and a footer with a back-link to the home page.

## Structure

```
.
├── index.html          # Landing page (project cards, footer)
├── project/            # Project detail pages
├── img/                # Images & project assets
│   ├── ECOTRA-PKMKC/
│   ├── KRTI/
│   └── robotik/
└── README.md
```

## Tech Stack

- **HTML5 & CSS3** — all styles inline per page, CSS custom properties for theming
- **Google Fonts** — Space Grotesk / Space Mono, Playfair Display, DM Sans, Inter
- **Responsive** — mobile-first breakpoints (720px / 560px / 480px)
- **Light/dark mode** — follows the OS setting on project pages; the home page is always dark

No dependencies, no build step.

## Run Locally

```bash
git clone https://github.com/Dickybulin26/Apple-Developer-Academy-Portofolio.git
cd Apple-Developer-Academy-Portofolio
```

Open `index.html` directly in a browser, or serve the folder:

```bash
npx serve .
```

## Contact

- Email: [dickyasqaelani@gmail.com](mailto:dickyasqaelani@gmail.com)
- LinkedIn: [linkedin.com/in/dicky-asqaeliany-ibnul-hakim](https://www.linkedin.com/in/dicky-asqaeliany-ibnul-hakim/)
- Instagram: [instagram.com/dicky_asqaelani26](https://www.instagram.com/dicky_asqaelani26)
