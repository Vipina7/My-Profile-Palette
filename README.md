# Vipina M — Portfolio Website

A one-page static portfolio site. Plain HTML, CSS and JavaScript — no build step, no framework, no backend.

## Files

- `index.html` — page content and structure
- `style.css` — all styling
- `script.js` — mobile navigation menu behavior
- `VIPINA_M_Resume.pdf` — the resume linked from the "Download resume" button

## Deploying to GitHub Pages (step by step)

1. **Create a GitHub account** at github.com if you don't already have one.
2. **Create a new repository**
   - Click the **+** icon (top right) → **New repository**.
   - Name it anything, e.g. `portfolio`. For a *personal* site at `yourusername.github.io`, name it exactly `yourusername.github.io` instead.
   - Keep it **Public**, and click **Create repository**.
3. **Upload the files**
   - On the new repo's page, click **Add file → Upload files**.
   - Drag in `index.html`, `style.css`, `script.js`, and `VIPINA_M_Resume.pdf`.
   - Click **Commit changes**.
4. **Turn on GitHub Pages**
   - Go to the repo's **Settings** tab → **Pages** (left sidebar).
   - Under **Build and deployment → Source**, choose **Deploy from a branch**.
   - Under **Branch**, choose `main` and folder `/ (root)`, then **Save**.
5. **Wait about a minute**, then refresh the Pages settings screen. GitHub will show your live URL:
   - `https://yourusername.github.io/portfolio/` (or `https://yourusername.github.io/` if you named the repo `yourusername.github.io`).
6. **Update the site later**: edit a file directly on GitHub (pencil icon) or re-upload it, commit, and the live site updates automatically within a minute or two.

No payment, server, or web-development experience is required — GitHub Pages hosts static files for free.

## Updating your details

- Contact links: search `index.html` for `mailto:` and `linkedin.com` and update them.
- Resume file: replace `VIPINA_M_Resume.pdf` with a new file of the same name, or update the `href` in the "Download resume" button in `index.html`.
