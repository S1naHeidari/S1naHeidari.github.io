# Sina Heidari — Personal Website

Landing page built with [Astro](https://astro.build) + [Tailwind CSS](https://tailwindcss.com), deployed to GitHub Pages.

## Develop

```sh
npm install
npm run dev      # live preview at http://localhost:4321
npm run build    # production build to dist/
```

## Deploy

Pushing to `main` triggers the GitHub Actions workflow (`.github/workflows/deploy.yml`) which builds and publishes the site. In the repo's **Settings → Pages**, the source must be set to **GitHub Actions**.

## Content

- Page content lives in `src/pages/index.astro` (bio, research cards, publications).
- Portrait images: `src/assets/portrait*.jpg`; social preview and favicon: `public/portrait-og.jpg`, `public/favicon.jpg`.
- CV PDF served from `public/cv.pdf` (source maintained on Overleaf).
