# IMF Calculator

A diet setup calculator for Lyle McDonald's book
[*Intermittent Modified Fasting*](https://store.bodyrecomposition.com/shop/intermittent-modified-fasting/) (2026).

**Live at [demin.ws/imf](https://demin.ws/imf/)**

## What it does

Given your bodyweight, body fat %, activity level, and training, it calculates
everything needed to set up an IMF diet following the charts in the book:

- **Diet category** (1/2/3) from the sex-specific body fat table, with a DEXA
  correction option, plus lean body mass and fat mass
- **RFL day** ("fasting" day) — minimum protein target scaled to category, lean
  body mass and training type; estimated calories, daily deficit, and fat loss
  per RFL day; fish oil (EPA/DHA) dose
- **Maintenance day** ("feasting" day) — TDEE via the book's method (BMR by
  category × activity and per-hour exercise multipliers), protein held equal to
  the RFL day, fat at 0.25–0.5 g/lb, carbohydrates from the remaining calories
- **Weekly plan** — a color-coded 7-day schedule for the chosen IMF pattern
  (6:1, 5:2, 4:3/3:4 alternate-day, ICR, 2:5, 1:6) with estimated weekly fat
  loss and total weekly deficit

Supports lb/kg, light/dark mode, and mobile widths. All values update live.

## Tech

A single self-contained `index.html` — vanilla JavaScript, no dependencies, no
build step. Open the file in a browser and it works.

Deployed with GitHub Pages.

## Disclaimer

The calculator only covers the basic setup — read the book for the full method.
Not medical advice: very-low-calorie days are not appropriate for everyone.
