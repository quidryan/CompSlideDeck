# Tech Compensation Slide Deck

A markdown-driven presentation covering RSU, ISO, and NQSO equity compensation.

Built with [Slidev](https://sli.dev/).

## Viewing

After publishing: `https://YOUR_USERNAME.github.io/CompSlideDeck/`

**Controls:** Arrow keys to navigate · `F` for fullscreen · `P` for presenter mode · `O` for slide overview

## Local Development

```zsh
npm install
npm run dev
# Opens at http://localhost:3030
```

## Building

```zsh
npm run build    # Static HTML to dist/
```

## Publishing to GitHub Pages

1. Push to the `main` branch
2. GitHub Actions builds and deploys automatically
3. One-time setup: **Settings → Pages → Source → GitHub Actions**

## Adding the Offer Letter Screenshot

Place a redacted offer letter image at `public/offer-letter.png`.
The RSU slides reference it at that path.

## Structure

| File | Purpose |
|---|---|
| `slides.md` | All slide content — edit this |
| `styles/index.css` | Custom callout boxes, table styles, layout helpers |
| `.github/workflows/deploy.yml` | Auto-deploy on push to main |
