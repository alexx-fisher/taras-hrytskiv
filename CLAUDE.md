# Taras Hrytskiv — Personal Website

## Project
Personal website for Taras Hrytskiv — barber, educator and mentor based in Los Angeles.

## Tech Stack
- Vanilla HTML + CSS (no frameworks)
- Google Fonts for typography
- Images pulled from Figma assets

## Design System
- Background: `#0c0c0c` (near black)
- Accent / secondary text: `#777165` (warm gray)
- Primary text: `#ffffff`
- Dark text / decorative: `#474747`
- Border radius for buttons: `150px` (pill shape)
- Font heading: Helvetica Neue Thin / Light (weight 100–300)
- Font script accent: Playball Regular
- Font nav / UI: Helvetica Neue Light (uppercase, tracked)

## Structure
Each section is a separate `<section>` in `index.html`.
Styles live in `styles/` — one CSS file per section (e.g. `styles/hero.css`).

## Workflow
- Blocks are added one at a time from Figma
- After each block is implemented, verify pixel-accurate layout against the Figma screenshot
- Do NOT add blocks or features that have not been explicitly requested

## File Layout
```
taras-hrytskiv/
  index.html
  styles/
    base.css
    hero.css
  assets/        ← downloaded images go here
```
