# Senpairyuulive — Personal Site

Lightweight, responsive single-page website for Senpai Ryuu.

Features
- 5 sections (Home, What I Build, Projects, Streams, Contact)
- Theme toggle (dark/light) with persisted preference
- LQIP blur-up avatar (assets/avatar-lq.jpg -> assets/avatar.jpg)
- Mailto contact form and copy-email button
- Social links: Discord, Instagram, YouTube
- Ready for GitHub Pages deployment

Local preview
1. Save the provided files in a folder and ensure there is an `assets/` folder with:
   - `assets/avatar.jpg` (the high-res avatar image you uploaded)
   - `assets/avatar-lq.jpg` (small blurred preview — see generation instructions below)
2. Start a local static server:
   - `python -m http.server` and open http://localhost:8000

Deploy to GitHub Pages
1. Create a repository named `Senpairyuulive` under your account (justtimmortal-debug) and push these files to the `main` branch.
2. In repository Settings → Pages, set Source to `main` branch (root) and save.
3. Pages URL: `https://justtimmortal-debug.github.io/Senpairyuulive`

Notes
- The contact form opens the user's mail client (no backend).
- Replace project placeholders with your real projects and update copy as needed.
- License: MIT (included)
