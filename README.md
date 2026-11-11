# Abdullah Al Miraj — Academic portfolio (redesigned)

A polished, editorial-style, responsive academic site ready for **GitHub Pages** at `https://miraj073.github.io/`.

## Publish

1. Create a **public** GitHub repository named `Miraj073.github.io` from your `Miraj073` account (or use that existing repository).
2. Upload the **contents** of this folder/ZIP to the repository root. `index.html` must be at the top level, beside `assets/`.
3. In the GitHub repository, choose **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
4. When the deployment is complete, visit `https://miraj073.github.io/`.

You can preview offline by opening `index.html` in a browser. A local server (`python -m http.server 8000`) is optional.

## Editing

- `index.html`: all copy, research, publications, roles, links, and SEO.
- `assets/styles.css`: color, typography, spacing, card layout, and mobile responsiveness.
- `assets/script.js`: mobile menu, publication filters, and active section navigation.
- `assets/*.svg`: original abstract illustrations and page branding. They can be replaced with your real lab photographs/SEM images.
- `assets/Abdullah_Al_Miraj_CV.pdf`: November 8, 2026 academic CV.

### Portrait

The small portrait on the hero board loads your public GitHub avatar (`github.com/Miraj073.png?size=240`) and falls back to initials if unavailable. For a custom portrait, place your photo at `assets/headshot.jpg` and replace the `src` of `id="profile-photo"` in `index.html`.

### Google Scholar

The Google Scholar link intentionally goes to a **search result** for your name, not a direct profile (no profile URL could be verified). Update when you provide the actual profile URL.

### Publications

Six peer-reviewed publications are listed, plus a separate **submitted manuscript**. Check publication statuses and your latest details before final publishing. Publication filters are client-side and need no external dependencies.

## Design & compatibility

- Warm editorial typography and a deep forest-green research feature area.
- Accessible high-contrast text, mobile-first navigation, keyboard support, and reduced-motion preference.
- Responsive desktop, tablet, and phone layouts.
- No frameworks/build steps; plain static HTML/CSS/JavaScript.
- Font files are **not** bundled; Google Fonts will load on connected browsers and system font fallbacks work offline.
