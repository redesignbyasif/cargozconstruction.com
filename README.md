# Cargoz Construction LLC — Homepage

A premium, fully responsive, static homepage redesign for **Cargoz Construction LLC**, a framing contractor based in Toms River, New Jersey, serving NJ, PA and NY.

Built as a static site (HTML5 + CSS3 + vanilla JavaScript) and ready to deploy on **GitHub Pages** — no build step, no backend, no server-side dependencies.

---

## Quick start

Because everything is static, you can open `index.html` directly, but for correct relative paths it is best served from a local server:

```bash
# from the repository root
python3 -m http.server 8080
# then open http://localhost:8080
```

## Project structure

```
.
├── index.html              # Homepage (single page)
├── css/
│   └── style.css           # Mobile-first stylesheet (design tokens + components)
├── js/
│   └── script.js           # Nav, reveal, counters, FAQ, filters (no dependencies)
├── assets/
│   ├── images/             # Photography & visual assets
│   ├── logo/               # Original company logo
│   └── icons/              # (icons are inline SVG in the markup)
├── .nojekyll               # Tells GitHub Pages to skip Jekyll processing
└── README.md
```

## Sections

1. Sticky navigation header with utility bar and mobile menu
2. Full-bleed hero with animated statistics
3. Services marquee
4. Core services showcase (6 services)
5. Featured work gallery with category filters
6. About / why-choose-us with feature list
7. Four-step work process
8. Service area
9. FAQ accordion
10. Final call-to-action
11. Footer with contact details
12. Floating call / request actions

## Technology

- **HTML5** — semantic, accessible markup (skip link, ARIA, landmarks)
- **CSS3** — custom properties, grid, flexbox, clamp() fluid type, no framework
- **Vanilla JavaScript** — mobile menu, scroll reveal, animated counters, FAQ accordion, gallery filters
- **Fonts** — Archivo + Inter via Google Fonts (with system-font fallbacks)
- **Icons** — inline SVG (no icon font dependency)

## Responsive & accessibility

- Mobile-first layout, targeting 360 / 390 / 430 / 768 / 1024 / 1280 / 1440px widths
- Fluid containers and images
- Touch-friendly targets, visible focus states, `prefers-reduced-motion` support
- Descriptive image alt text and colour-contrast-aware palette

## Deployment (GitHub Pages)

1. Push this branch to GitHub.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Select the branch and the `/ (root)` folder, then **Save**.
5. The site is published at `https://<username>.github.io/<repository>/`.

All asset paths are relative, so the site also works from a project subdirectory.

---

© Cargoz Construction LLC. Redesign concept demo.
