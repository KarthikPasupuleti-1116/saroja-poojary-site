# Coastal Kitchen (Saroja Poojary)

This repository hosts the static site located at `public/site.html` (redirected from `/`). It is configured as a Next.js project so it can be deployed cleanly on Vercel.

## How it works

- The full HTML site is stored in: `public/site.html`
- Visiting `/` redirects to `/site.html` (via `src/app/page.tsx`)

## Run locally

```bash
npm install
npm run dev
```

Then visit:

- http://localhost:3000 (redirects to `/site.html`)

## Deploy to GitHub + Vercel

1. Create a repository under the GitHub account `KarthikPasupuleti-1116` (e.g. `saroja-poojary-site`).
2. In this project, set the remote URL and push:

```bash
git remote set-url origin https://github.com/KarthikPasupuleti-1116/<repo-name>.git
git push -u origin main
```

3. Import the repo into Vercel and deploy (Vercel automatically detects Next.js).

---

> If you want this to be served directly at `/` (without a redirect), I can add a `vercel.json` configuration to make `public/site.html` the root output directly.
