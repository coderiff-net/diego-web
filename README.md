# Diego Martin — personal website

Personal CV and contact website built with Astro, Tailwind CSS, and Astro Icon. The blog is hosted externally at [coderiff.net/blog](https://coderiff.net/blog/).

## Develop

```sh
npm ci
npm run dev
```

## Build

```sh
npm run build
npm run preview
```

The static site is published to GitHub Pages by `.github/workflows/ci-deploy.yaml` at `diego.coderiff.net`.

The main page sections live in `src/components/portfolio`. The portrait is `public/images/diego-pic.jpg`.
