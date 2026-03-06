# polybjorn.no

Personlig portefølje og kontaktpunkt. Distribusjonsmål — kildekoden ligger i [polybjorn/polybjorn-en](https://github.com/polybjorn/polybjorn-en).

- [polybjorn.no](https://polybjorn.no) — Norsk
- [polybjorn.com](https://polybjorn.com) — Engelsk

## Teknologi

- [Astro](https://astro.build) — statisk nettstedsgenerator
- [Cloudflare](https://cloudflare.com) — DNS
- [Cloudinary](https://cloudinary.com) — bildehosting og transformasjoner
- [GitHub Pages](https://pages.github.com) — hosting
- [GitHub Actions](https://github.com/features/actions) — distribusjon ved push
- [Umami](https://umami.is) — informasjonskapselløs, personvernvennlig analyse

## Ressurser

- [flag-icons](https://flagicons.lipis.dev) — flagg
- [Icons8](https://icons8.com) — ikoner
- [Lucide](https://lucide.dev) — ikoner
- [Piazzolla](https://fontsource.org/fonts/piazzolla) — skrifttype
- [rough-notation](https://roughnotation.com) — håndtegnede understrekingsanimasjoner

## Struktur

```
src/
  layouts/Layout.astro      — felles layout
  pages/                    — engelske sider
  pages/no/                 — norske sider
  data/                     — innhold som JS-objekter
scripts/
  prepare-deploy.mjs        — forbereder deploy til to repoer
```

## Personvern

- Ingen annonser eller tredjepartssporing
- Analyse via Umami — uten informasjonskapsler, ingen persondata samles inn
- Kontaktinfo kodet i HTML for å redusere skraping
