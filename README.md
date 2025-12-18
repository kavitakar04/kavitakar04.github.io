# kavita kar — personal site

This repository hosts my personal website, built with static HTML/CSS and deployed via GitHub Pages.

Live site: https://kavitakar04.github.io

## Structure

- `index.html` — homepage with sections for projects, writing, and contact.
- `thoughts/` — blog-like section with an index and individual posts.
  - `thoughts/index.html` lists posts and links to each.
  - `thoughts/*.html` are standalone posts that link back to the list.
- `assets/` — static files (images, pdfs, fonts). See `assets/README.md`.
- `styles.css`, `script.js` — shared styles and behavior.

## Linking posts and assets

- Writing cards on the homepage link to:
  - `thoughts/ai-in-education.html`
  - `thoughts/quant-research-notes.html`
  - `thoughts/tools-i-like-building.html`
- Add new pieces by duplicating a post in `thoughts/` and adding it to `thoughts/index.html`.
- Reference assets with relative paths, e.g. `assets/images/my-image.png` or `assets/pdf/KavitaKar_Resume.pdf`.
