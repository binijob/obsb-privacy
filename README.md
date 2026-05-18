# OBSB Privacy Policy & Legal Pages

Static legal pages for the **OBSB Chrome Extension**, served via GitHub Pages (or Vercel).

## Pages

| Page | URL (after deploy) |
|------|-------------------|
| Home | `https://binijob.github.io/obsb-privacy/` |
| Privacy Policy | `https://binijob.github.io/obsb-privacy/privacy.html` |
| Terms & Conditions | `https://binijob.github.io/obsb-privacy/terms.html` |

## Deploy on GitHub Pages (free, recommended)

1. **Create the repo** on GitHub — name it `obsb-privacy` (or any name you like).
2. **Push these files** to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial legal pages"
   git remote add origin https://github.com/binijob/obsb-privacy.git
   git push -u origin main
   ```
3. **Enable GitHub Pages**:
   - Go to repo → **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` / `/ (root)`
   - Click **Save**
4. After ~60 seconds your site is live at:
   `https://binijob.github.io/obsb-privacy/`





## File structure

```
obsb-privacy/
├── index.html        ← landing page linking to both docs
├── privacy.html      ← Privacy Policy
└── terms.html        ← Terms and Conditions
```

No build step, no dependencies, no Node.js. Pure HTML + CSS.
