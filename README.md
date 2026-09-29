# GitHub Pages: React + Vite

A starter React + TypeScript app built with Vite, used to try out deploying React to GitHub Pages.

**Live site:** https://ghorbel37.github.io/gh-pages-react/

## How it's deployed

- `vite.config.ts` sets `base: '/gh-pages-react/'` so assets load from the repository's Pages path.
- `npm run deploy` builds the app and pushes the `dist/` folder to the `gh-pages` branch with the [`gh-pages`](https://www.npmjs.com/package/gh-pages) package.
- GitHub Pages serves the `gh-pages` branch.

```bash
npm install
npm run build
npm run deploy
```

## Run locally

```bash
npm run dev
```

## Related experiments

- [gh-pages-html-test](https://github.com/Ghorbel37/gh-pages-html-test): the same with plain HTML
- [gh-pages-ng](https://github.com/Ghorbel37/gh-pages-ng): the same with an Angular app
