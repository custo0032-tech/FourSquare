# FourSquare — AI Startup Safe Haven Informational Website

A responsive, static company landing page for AI Startup Safe Haven.

## Included
- `index.html` — page structure and company copy
- `styles.css` — responsive dark graphite / violet visual system
- `script.js` — mobile navigation, current year, and reveal effects
- `vercel.json` — static hosting configuration

## Preview locally
Open `index.html` in your browser. For a local web server, run:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000`.

## Deploy to Vercel (recommended: GitHub import)
1. Create or sign in to GitHub.
2. Create a new repository named `ai-startup-safe-haven`.
3. Upload `index.html`, `styles.css`, `script.js`, and `vercel.json` from this folder to the repository root.
4. Sign in at https://vercel.com and choose **Add New → Project**.
5. Import the GitHub repository.
6. For a plain static website, leave the framework preset as **Other**. Leave Build Command blank and Output Directory as `.` (or the default static setting if Vercel detects it).
7. Click **Deploy**. Vercel will provide a public URL.
8. After the first deployment, use **Settings → Domains** if you want to connect a custom domain.

## Before publishing
- The contact buttons use `1ep23ci014@gmail.com`.
- The page is a public company/brand website. It does not yet include sign-in, a backend, AI agent execution, a database, or a working product dashboard.
- Fonts load from Google Fonts; system fallbacks are included.
