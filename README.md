# OBSB Privacy Policy & Legal Pages

Static legal pages for the **OBSB Chrome Extension**, served via GitHub Pages (or Vercel).

## Pages

| Page | URL (after deploy) |
|------|-------------------|
| Home | `https://YOUR_USERNAME.github.io/obsb-privacy/` |
| Privacy Policy | `https://YOUR_USERNAME.github.io/obsb-privacy/privacy.html` |
| Terms & Conditions | `https://YOUR_USERNAME.github.io/obsb-privacy/terms.html` |

## Deploy on GitHub Pages (free, recommended)

1. **Create the repo** on GitHub — name it `obsb-privacy` (or any name you like).
2. **Push these files** to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial legal pages"
   git remote add origin https://github.com/YOUR_USERNAME/obsb-privacy.git
   git push -u origin main
   ```
3. **Enable GitHub Pages**:
   - Go to repo → **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` / `/ (root)`
   - Click **Save**
4. After ~60 seconds your site is live at:
   `https://YOUR_USERNAME.github.io/obsb-privacy/`

## Deploy on Vercel (alternative, also free)

1. Push the repo to GitHub (step 1–2 above).
2. Go to [vercel.com](https://vercel.com) → **Add New Project** → import your GitHub repo.
3. Framework Preset: **Other** (it's plain HTML, no build step needed).
4. Click **Deploy** — you'll get a `*.vercel.app` URL immediately.
5. Optionally add a custom domain in Vercel's project settings.

## Customisation

- Replace `YOUR_USERNAME` references in links throughout the HTML files.
- Update `privacy@obsb.app` with your actual contact email.
- Edit the content of each page to match your extension's exact behaviour.
- The **Last updated** date is in the `<p class="meta">` element near the top of each page.

## File structure

```
obsb-privacy/
├── index.html        ← landing page linking to both docs
├── privacy.html      ← Privacy Policy
└── terms.html        ← Terms and Conditions
```

No build step, no dependencies, no Node.js. Pure HTML + CSS.
