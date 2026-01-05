# omnirepo.org

Marketing site for the Omnirepo pattern: structuring organizations for AI.

## Development

```bash
npm install
npm run dev      # localhost:4321
```

## Build & Deploy

```bash
npm run build    # outputs to ./dist/
npm run preview  # preview production build
```

Deployed to GitHub Pages at [www.omnirepo.org](https://www.omnirepo.org).

## Email Signup

Uses [Kit](https://kit.com) (ConvertKit) for email capture. Form is embedded via script tag and styled in Kit's dashboard.

## Structure

```
src/
  layouts/Layout.astro   # SEO, meta tags, fonts
  pages/index.astro      # Single page site
public/
  og-image.png           # Social sharing image
  robots.txt             # Search engine rules
  favicon.svg
```
