# Block Dodger (single-file)

This repo contains a single `index.html` web game that runs on any modern browser and can be deployed with GitHub Pages.

## Local run
Open `index.html` directly in your browser.

## Deploy with GitHub Pages (UI)
1. Create a new repo (Public) on GitHub and upload `index.html`.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose **Branch: `main`** and **Folder: `/ (root)`**, then **Save**.
5. Your site will be available at `https://<username>.github.io/<repo>/`.

## Deploy with Git (CLI)
```bash
git init
git add index.html README.md
git commit -m "Deploy Block Dodger"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
# Then enable GitHub Pages: Settings → Pages → Source: Deploy from a branch → Branch: main, Folder: /(root)
```

## Controls
- Desktop: A/D or ◀ ▶ to move, Space to start, R to restart.
- Mobile: on-screen buttons; tap to start/restart.

Kudos & enjoy!
