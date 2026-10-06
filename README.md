# Tran Chanh Dat — Astro Portfolio

## Run locally
Requirements: Node.js 22.12+ (current LTS recommended), VS Code, Astro extension.

```bash
npm install
npm run dev
```

Open the URL shown by Astro, normally http://localhost:4321

## Production test
```bash
npm run build
npm run preview
```

## GitHub Pages
Change `site` in `astro.config.mjs` to your real GitHub Pages URL. Push to GitHub and set Pages → Source → GitHub Actions.
If the repository is `USERNAME.github.io`, no `base` is required. Otherwise add `base: '/REPOSITORY-NAME'`.
