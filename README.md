# Bini & Bethy's Wedding Pamphlet (11.21.26)

A single-page interactive version of the printed pamphlet. Plain HTML, CSS and JavaScript, with no build step.

- `index.html` is the whole page (CSS and JS are inline).
- `img/` holds the images.
- `.nojekyll` tells GitHub Pages to serve the files as they are.

Fonts load from Google Fonts, so the page needs an internet connection to show the intended typefaces.

## Host it on GitHub Pages

1. Create a new GitHub repository and upload everything in this folder (keep `index.html`, `img/` and `.nojekyll` at the top level).
2. Open **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

For a custom domain, add it under Settings → Pages → Custom domain and point a DNS CNAME record at `<your-username>.github.io`.

## QR code on the printed pamphlet

Point the QR code at the final address from step 4.
