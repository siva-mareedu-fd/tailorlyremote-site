# Tailorly Remote: public website

Static landing page for Tailorly Remote (https://professional.tailorlyremote.com). One HTML file, no build step.

## Files
- `index.html`  the whole site (HTML, CSS and a few lines of JavaScript; fonts from Google Fonts)
- `_headers`    security headers (used by Cloudflare Pages and Netlify; ignored by GitHub Pages)

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server 8000` and visit http://localhost:8000.

## Deploy
Option A, Cloudflare Pages from this repo: Workers & Pages > Create > Pages > Connect to Git > pick this repo. Build command: none. Output directory: `/` (the repo root). Then add your custom domain.
Option B, GitHub Pages: repo Settings > Pages > deploy from the `main` branch, root folder. Add the custom domain in the same screen.

## Things to keep on this page
- The credits and links to Himalayas and Remote OK (required by their terms). They appear under "Jobs sourced from", in "Sources and credits", and in the footer.
- Estimated labels on ATS scores. Do not promise outcomes.

## Editing
Contact email, copy and links are plain text in `index.html`. After editing, commit and push; the host redeploys automatically.
