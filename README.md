# Abdullah Al Miraj — Academic Portfolio

A professional, responsive academic website prepared for **GitHub Pages** at **https://miraj073.github.io/**.

Built using plain HTML, CSS, and JavaScript (no frameworks, dependencies, build process, or hosting fees required). Content is adapted from the public Google Site and updated using the November 8, 2026 academic CV.

## Publish it to GitHub Pages

1. Sign in to GitHub as **Miraj073**.
2. Create a **public** repository named exactly **`Miraj073.github.io`**. Repository names are case-insensitive, but the `username.github.io` convention matters.
3. Upload **all files and folders from this ZIP**, directly to the repository's root (not inside an extra enclosing folder). Make sure `index.html` is at the root and `assets/` is beside it.
   - GitHub website: **Add file → Upload files → Commit changes**.
   - Alternatively, use Git from a folder containing `index.html`: `git init`, `git add .`, `git commit -m "Launch academic portfolio"`, `git branch -M main`, `git remote add origin https://github.com/Miraj073/Miraj073.github.io.git`, `git push -u origin main`.
4. Go to repository **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, then **main** and **/(root)**, then **Save**.
5. Open **https://miraj073.github.io/** when GitHub Pages indicates deployment has completed.

You can preview it locally by double-clicking `index.html` or running `python -m http.server 8000` in the folder and opening `http://localhost:8000`.

## Where to edit

- **`index.html`** — all text, publications, projects, roles, links, and SEO metadata.
- **`assets/styles.css`** — typography, layout, palette, and responsive design.
- **`assets/script.js`** — mobile menu, publication filters, smooth navigation behaviors, and photo fallback.
- **`assets/Abdullah_Al_Miraj_CV.pdf`** — downloadable academic CV, from your November 8 version.
- **`assets/*.svg`** — custom vector research/project illustrations, website icon, and sharing preview.

### Personal photo

The portrait automatically uses your **GitHub account avatar** via `https://github.com/Miraj073.png?size=600`. If it cannot load, a graceful initials placeholder is shown. For the most reliable long-term result, copy your preferred portrait as `assets/headshot.jpg`, then replace the `src` of `<img id="profile-photo">` in `index.html` with `assets/headshot.jpg`. The Google Site profile photo is not bundled because it is not available as a stable local source file.

### Google Scholar

The Google Scholar button currently opens a **search** for your name, not a verified public Scholar profile. When you have your direct profile URL, replace `https://scholar.google.com/scholar?q=%22Abdullah+Al+Miraj%22` in `index.html` with that URL and change the label to `Google Scholar`.

### Update publication records

Six peer-reviewed publications are listed, plus one submitted manuscript separately. Add DOI links and update manuscript status as it changes. Some research outcomes and publication dates should be reviewed before public launch.

## Built-in features

- Responsive desktop/tablet/mobile layouts
- Accessible navigation and reduced-motion support
- Interactive publication year filters
- Functional email, LinkedIn, GitHub, paper DOI, and CV links
- Semantic headings, SEO metadata, social sharing image, favicon, JSON-LD Person schema
- Zero build tools; compatible with free GitHub Pages static hosting

## Attribution

Research and career content: Abdullah Al Miraj. Original editorial layout and SVG diagrams created for this website. No affiliation endorsement is implied.
