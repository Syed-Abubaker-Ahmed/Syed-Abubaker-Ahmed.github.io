# Syed Abubaker Ahmed — Business Analyst Portfolio

A single-page portfolio for a Business Analyst with a software engineering background: requirements,
process analysis, data modelling and delivery planning, with the technical specs written in-house rather
than handed off to a separate engineering team.

Live at [Syed-Abubaker-Ahmed.github.io](https://syed-abubaker-ahmed.github.io).

---

## Overview

One self-contained `index.html` — no frameworks, no build step, no external requests. The variable font is
embedded directly in the file, so the page renders and works fully offline after the first load.

## Features

- Fixed identity rail on desktop (collapses to a top bar with a menu on mobile)
- Scroll-driven reveal animations via native CSS (`animation-timeline`), with a small JS fallback for
  browsers that don't yet support it
- Hero load-in sequence and parallax drift, section-heading wipe reveals
- Animated count-up on the proof-point statistics
- Cursor-follow marker on pointer devices
- One embedded variable font (Recursive) supplying both the display sans and the monospace accents from a
  single file
- Fully responsive, keyboard-accessible, respects `prefers-reduced-motion` and `prefers-color-scheme`

## Tech Stack

- HTML5 + CSS3 (custom properties, native scroll-driven animations)
- Vanilla JavaScript (progressive enhancement only — nothing on the page depends on it to be readable)
- [Recursive](https://www.recursive.design/) variable font (OFL), embedded as base64 `woff2`
- Zero frameworks, zero external requests

## Project Structure

```
├── index.html
└── Syed Abubaker Ahmed.pdf
```

## Sections

- About
- Experience
- Projects
- Education
- Contact

## Résumé

Downloadable directly from the site's contact section, or here: [Syed Abubaker Ahmed.pdf](Syed%20Abubaker%20Ahmed.pdf)

## Contact

- **Email**: sabubakerahmed@gmail.com
- **LinkedIn**: [linkedin.com/in/syed-abubaker-ahmed](https://www.linkedin.com/in/syed-abubaker-ahmed/)
- **GitHub**: [github.com/Syed-Abubaker-Ahmed](https://github.com/Syed-Abubaker-Ahmed)

---

Built by Syed Abubaker Ahmed
