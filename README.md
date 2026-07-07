<div align="center">

# Labiba Bushra Zeba — Personal Portfolio

**Business × Emerging Technology**

A cinematic, single-file personal portfolio website. Dark, glass, and interactive — built to make a strong first impression in the first five seconds.

[![Live Site](https://img.shields.io/badge/Live-Portfolio-38BDF8?style=for-the-badge)](#-deploy)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)

</div>

---

## Overview

This is the personal portfolio of **Labiba Bushra Zeba** — a final-year BBA candidate at United International University and a **Blockchain Olympiad Bangladesh 2025 finalist**. The site tells a story rather than listing facts: education, capabilities, real experience, recognition, and a photo gallery, all wrapped in a premium dark interface.

The entire site is **one self-contained `index.html`** — the images and CV are embedded, so it works offline and deploys anywhere with zero build steps.

## Features

- **Cinematic hero** — animated name reveal, gradient headline, floating glass stat-cards, and a 3D tilt on the portrait
- **Custom cursor** with a mouse-follow ambient glow
- **Particle field** and animated aurora background
- **Scroll progress bar**, active-section nav highlighting, and a back-to-top button
- **Reveal-on-scroll** animations and **animated counters**
- **Interactive timelines** for education and experience
- **Featured highlight block** for the Blockchain Olympiad achievement
- **Skills grid** with hover spotlight effects
- **Photo gallery** with a click-to-open lightbox
- **Testimonial** and a **mailto-powered contact form**
- **Dark / light theme toggle**
- **Fully responsive** (mobile-first) with keyboard focus and reduced-motion support
- **Working "Download CV"** button (PDF embedded)

## Tech

- Semantic **HTML5**
- **CSS3** — custom properties, `backdrop-filter` glassmorphism, grid & flexbox, keyframe animations
- Vanilla **JavaScript** — `IntersectionObserver`, `requestAnimationFrame`, Canvas particles
- **Google Fonts** — Space Grotesk (display), Inter (body), Space Mono (labels)
- No frameworks, no build tools, no dependencies to install

> **Design tokens:** `#050816` background · `#38BDF8` blue · `#7C3AED` violet · `#22D3EE` cyan

## Project structure

```
.
├── index.html      # The entire site — markup, styles, scripts, and embedded assets
└── README.md       # This file
```

## Getting started

Clone the repository and open the file — that's it.

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```

Then open `index.html` in any browser, or serve it locally:

```bash
# Python
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Because it is a single static file, deployment takes seconds.

### GitHub Pages
1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, pick the `main` branch and the `/root` folder, then **Save**.
4. Your site goes live at `https://<your-username>.github.io/<your-repo>/`.

### Netlify
- Drag the project folder onto [Netlify Drop](https://app.netlify.com/drop), or connect the repo for automatic deploys.

### Vercel
```bash
npm i -g vercel
vercel
```

## Customization

Everything lives in `index.html`:

- **Colors** — edit the CSS variables in the `:root` block near the top.
- **Fonts** — swap the Google Fonts `<link>` and the `font-family` declarations.
- **Content** — update the text directly in the corresponding `<section>` blocks.
- **Images / CV** — replace the embedded `data:` URLs, or point to external files (e.g. `assets/photo.jpg`).

## Sections

`Hero` · `About` · `Education` · `Skills` · `Highlights & Experience` · `Achievements` · `Gallery` · `Testimonial` · `Contact`

## Contact

- **Email:** labibabushra18@gmail.com
- **LinkedIn:** [linkedin.com/in/labiba-bushra-zeba](https://www.linkedin.com/in/labiba-bushra-zeba-63b9a0389)
- **Location:** Bashundhara R/A, Dhaka, Bangladesh

---

<div align="center">

© 2026 **Labiba Bushra Zeba** · Designed with intent.

</div>
