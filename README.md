# Ashu — Will you be my Valentine?

Simple single-file Valentine page ready to share.

What’s included
- `index.html` — the full page. Replace the placeholder image/GIF URLs with your own assets.
- Social meta tags (Open Graph & Twitter) so links render nicely on messaging apps.
- A Share button that uses the Web Share API where available, falling back to copying the page URL to the clipboard.

Customize
- Edit the page title and main text in `index.html` (currently: "Ashu will you be my Valentine?").
- Replace these placeholders in `index.html`:
  - `YOUR_IMAGE_URL_OR_FILENAME_HERE` — your profile photo (or remove the `img` tag).
  - `YOUR_DOG_GIF_URL_OR_FILENAME_HERE` — optional celebration GIF.
  - `OG_IMAGE_URL` in the Open Graph meta tag — optional social preview image URL.

Deploy options

1) GitHub Pages (recommended for a quick free share link)
- Create a repository (or use this repo).
- Push `index.html` to the repository root on the `main` branch.
- In the repository Settings → Pages, set Source to branch `main` (root).
- Your site will be available at `https://<your-username>.github.io/<repo>/` (or at `https://<your-username>.github.io/` if repo named `<your-username>.github.io`).

2) Netlify (drag & drop)
- Go to Netlify and use the "Sites" → "Add new site" → "Deploy manually" → drag & drop the repository folder (or just the `index.html` file).
- Or connect your GitHub repo for continuous deploys.

3) Vercel
- Use Vercel and import the GitHub repository. It auto-deploys static files.

4) Quick share (no deploy)
- Use a raw file host like [raw.githack.com](https://raw.githack.com/) to preview a single HTML file:
  - Raw URL: `https://raw.githubusercontent.com/<user>/<repo>/<branch>/index.html`
  - Convert it with raw.githack: `https://raw.githack.com/<user>/<repo>/<branch>/index.html`

Notes
- Accessibility: the NO button is keyboard-focusable and has an “escape hatch” so it becomes clickable after a few dodges to avoid frustration.
- If you want, I can commit these files into your `nishatambe/scamlink.co` repo and set up a GitHub Pages branch. Tell me which branch to use (e.g., `main` or `gh-pages`) and confirm.

License
- This template is free to use; let me know if you want a specific license file added.