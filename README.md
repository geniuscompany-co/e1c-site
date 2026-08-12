# E1C.net

Marketing site for E1C (Entrepreneur's First Choice) — built with [Astro](https://astro.build).

## Pages

- `/` — Home
- `/the-first-strategy/` — The First Strategy framework, with an email-gated guide download
- `/apps/` — Entrepreneur apps (coming soon)
- `/about/` — About E1C
- `/contact/` — Contact

## Brand

- Background: `#FBF7EF` (cream)
- Text / accent: `#16233E` (navy) — two-tone palette, no secondary accent color
- Headings: Fraunces (serif) · Body: Inter — loaded from Google Fonts in `Layout.astro`

## Known gaps before launch

- **Email forms have no backend.** The email-gate form on `/the-first-strategy/` and the notify-me form on `/apps/` are static HTML with no submission handler. Connect a service like ConvertKit, Mailchimp, or Formspree before launch.
- **About page copy is a placeholder.** It's written from the framework/philosophy, not a real founder bio — swap in the real story before launch.
- **No photography.** By design — the brand direction is flat/typographic, not photo-based. A small navy circle mark stands in for imagery.

## Local development

```
npm install
npm run dev
```

## Build

```
npm run build
```

Outputs static files to `dist/`.


_GA4 tracking added._
