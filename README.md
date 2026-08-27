# Benjamin Rigó — Portfolio

Personal portfolio site for Benjamin Rigó, Lead Product Designer. A single self-contained `index.html` — no framework, no build step, no dependencies. Hash-routed (`#work`, `#work/<slug>`, `#about`), with case studies for NXLog Platform, BKK Pay&Go, a genericized FinTech engagement, and a genericized CO2-capture monitoring project.

## Running locally

No build step — just serve the file:

```bash
python3 -m http.server 8000
# or
npx serve .
```

Then open `http://localhost:8000`.

## Deploying

Static single-file site — deploys as-is to any static host (Vercel, Netlify, GitHub Pages, etc.). No build command, no output directory beyond the repo root.

## Structure

- `index.html` — the entire site: markup, CSS, and JS in one file.

## Notes

- Design system: 3 colors (`--bg`, `--ink`, `--ink-dim`), system font stack (no webfont), consolidated type scale.
- Mobile-responsive down to ~375px, with a dedicated tablet tier for 701–1150px viewports.
- Accessibility: real heading hierarchy, focus-visible states, `aria-live` copy feedback, `prefers-reduced-motion` support, WCAG AA contrast.
- Text/image selection and right-click are disabled site-wide (email is still copyable via its own click handler).

© 2026 Benjamin Rigó. All rights reserved.
