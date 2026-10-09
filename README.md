# VECTRA — Orbital Telemetry

A single-file, scroll-driven landing page for a fictional orbital telemetry product.
No build step and no dependencies beyond Google Fonts.

## Run locally

```bash
python3 -m http.server 8765
```

Then open http://localhost:8765/vectra.html.

## What's inside

- `vectra.html` — the whole page: styles, markup and the canvas/SVG animations.
- Eight pinned sections driven by scroll progress (`--p` / `--q` custom properties).
- A canvas starfield and wireframe globe that re-frames itself per section.
- Respects `prefers-reduced-motion` and degrades without JavaScript.
