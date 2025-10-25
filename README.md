# Serene Harmony — Stretch Professional Site (Starter)

This package contains a mobile-friendly, single-file website tailored for a stretching professional, with on-brand colors, elegant typography, soft edges, and a subtle paisley texture.

## Contents
- `index.html` — the site
- `assets/paisley.svg` — light seamless-style background
- `assets/living-marvel.svg`, `assets/sacred-balance.svg`, `assets/conclusion.svg` — neutral hero/section placeholders you can replace anytime

## Customize
- Replace the three section images in `/assets/` with your own photos (keep names or update the `src` paths in `index.html`).
- To adjust the paisley texture strength, edit `opacity` in the `body::before` CSS (0.18–0.35 recommended).

## Lead Capture (Two Options)

### A) Netlify Forms (zero JS)
1. Drag-drop this folder into Netlify (or connect a repo).
2. Visit the deployed site once; Netlify will auto-detect the form named `stretch-contact`.
3. In Netlify → Forms, enable notifications as desired.

### B) Formspree (works anywhere)
1. Create a Formspree form → get your endpoint ID.
2. In `index.html`, change the `<form>` tag to:
   ```html
   <form action="https://formspree.io/f/YOUR_ID" method="POST" class="stack">
   ```
3. Remove `data-netlify` and the hidden `form-name` + honeypot if you like.

## Hosting
- **GitHub Pages**: push to a repo, enable Pages; put files at repo root or `/docs`.
- **Netlify / Cloudflare Pages / Vercel**: drag-and-drop or connect your repo. No build step required.

## Squarespace (optional)
- Copy each section’s text into Squarespace sections.
- Add the small Custom CSS snippet (paisley layer + soft edges).
- Use Squarespace’s native Form block for submissions.

## License
You can use and modify this for personal or client work. Replace images as needed.
