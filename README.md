# Animated Icon Library

A collection of Salesforce product icons with GSAP-powered hover animations. Each icon has flat (vector SVG) and 3D (raster) variants with a toggle, plus a full-screen animation editor where you can tweak motion parameters and export self-contained code.

## Live Demo

https://anishabhatt7.github.io/animated-icon-library/

## Icons

| Icon | Animation Style |
|------|----------------|
| Service | Heartbeat pulse with elastic bounce |
| Agentforce | Power-up float with spectacles squish |
| Sales | Square tilt + graph arrow rise |
| Slack | Staggered arm spread + dot pop |

## Features

- **Hover animations** — each icon animates on hover with motion tailored to its shape
- **Flat / 3D toggle** — switch between vector SVG and 3D raster variants
- **Dark / Light theme** — toggle via the sun/moon button
- **Animation Editor** — open any icon in a full-screen playground with 10 tweakable motion levers (duration, delay, easing, scale, rotation, Y offset, color shift, blur, opacity, elasticity)
- **Export** — copy self-contained code in 3 formats:
  - **GSAP** — HTML + inline SVG + GSAP animation script
  - **JSON** — serialized config with SVG markup
  - **CSS** — pure `@keyframes` animation, no JS needed

All exports inline the full SVG markup so they work out of the box when pasted into any HTML file.

## Tech

- [GSAP 3.12.5](https://greensock.com/gsap/) for animations
- [Figtree](https://fonts.google.com/specimen/Figtree) font
- Single self-contained `index.html` — no build step, no dependencies beyond the GSAP CDN

## Usage

Open `index.html` in a browser. That's it.
