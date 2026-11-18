# .github

Organization-level GitHub configuration for [Vibewatch](https://vibewatch.io).

- [`profile/README.md`](profile/README.md) renders as the public org profile at [github.com/Vibewatch-io](https://github.com/Vibewatch-io).
- [`profile/assets/`](profile/assets/) holds the brand assets used by that profile: the hero banner, logo lockups and symbol.

`profile/assets/hero.png` is the Vibewatch 2.0 share banner (wordmark, category line and headline beside the Engage window). It is rendered by `hero-kit/render-banners.mjs` in the internal `vibewatch-marketing` repo, which also holds its source PNG (`hero-kit/banners/github-org-hero-1280x400.png`). When the category line or the homepage hero changes, re-render it there and replace this file with the new export.

Brand source of truth lives in the internal `vibewatch-docs` repo: `brand/STYLE_GUIDE.md` for design, `brand/VOICE.md` for copy. Keep the palette, wordmark, and wording here in sync with them.
