# Neuromancer CSS

A cyberpunk look for Bootstrap: black, turquoise and yellow, clipped corners, HUD panels and glitch buttons. Drop it in after Bootstrap 4.x or 5.x; no build step.

## Usage

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/joelcancela/Neuromancer.css@v1.0.0/neuromancer.css">
```

Load it after Bootstrap. Colors, glow, typography and spacing live in `--sf-*` custom properties on `:root`, so they can be overridden.

## Fonts

Oxanium (text) and Rajdhani (headings) are loaded from Google Fonts with an `@import` at the top of `neuromancer.css`. No font file is stored in this repository. To avoid the request to Google, remove the `@import` and self-host both families under the same names.

## What is themed

- Bootstrap 4/5 naming differences are covered where needed (for example `.badge-primary`/`.bg-primary` and `.close`/`.btn-close`).
- Buttons use a clipped lower-right corner; outline variants use an inset pseudo-element because `clip-path` clips ordinary borders and shadows.
- HUD panels, tabs, forms, tables, dropdowns, pagination, badges, alerts and modal controls.
- Reusable classes: `.sf-panel`, `.sf-card`, `.sf-filter`, `.sf-chip`, `.sf-box`, `.sf-footer`, `.sf-accent`, `.sf-title-bar`, `.sf-text-outline`, `.sf-link-caps`.
- `prefers-reduced-motion` turns off the transitions and animations.

## License

[MIT](LICENSE). Oxanium and Rajdhani are distributed by Google Fonts under the SIL Open Font License 1.1 and keep their own terms.