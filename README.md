# JanSetu AI

A prototype welfare & grievance platform (React + Vite).

## Run locally

```bash
npm install
npm run dev
```

Then open the URL Vite prints (usually http://localhost:5173).

## Build for production

```bash
npm run build
npm run preview
```

## Connect to a git repo

```bash
git init
git add .
git commit -m "Initial commit: JanSetu AI prototype"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

(Create the empty repo on GitHub first, then paste its URL into the `remote add` command above.)

## Deploy

Any static host that supports Vite/React works. Easiest options:

- **Vercel** — import the GitHub repo at vercel.com/new, it auto-detects Vite, no config needed.
- **Netlify** — import the repo at app.netlify.com, build command `npm run build`, publish directory `dist`.
- **GitHub Pages** — run `npm run build`, then deploy the `dist` folder (e.g. with the `gh-pages` npm package).
