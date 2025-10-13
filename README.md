# Rust Systems Engineer Landing Page

Static marketing site for Grzegorz Aleksander Klementowski, focused on Rust systems engineering services. The site showcases service offerings, case studies, process, and contact information.

## Structure
- `index.html` – main page markup with intro hero, services, case studies, and process timeline
- `styles.css` – layout, typography, and responsive styling
- `rust-logo-gear.png`, `rust-logo-crab.png` – brand imagery used in the hero and header

## Getting Started
1. Clone or download this repository.
2. Open `index.html` in your browser to view the site.
   - Optionally run a lightweight server, e.g. `python -m http.server`, to test relative paths and assets locally.

## Customisation Tips
- Update contact details, metrics, and service descriptions inside `index.html` to match new offerings.
- Add or replace images in the `img` tags if you want different branding. Keep associated dimensions in `styles.css` aligned.
- Adjust colours, spacing, or typography inside `styles.css`. Media queries near the end of the file handle smaller viewports.

## Deployment
This is a static site; deploy it to any static host (GitHub Pages, Netlify, Vercel, S3, etc.). Ensure both PNG assets and `styles.css` are uploaded alongside `index.html`.
