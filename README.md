# Saravana Agencies

A static marketing website for **Saravana Agencies**, a trusted supplier of premium construction materials including cement, steel, sand, blue metals, AAC blocks, and more.

## Overview

This single-page website showcases the company's products and services with a modern, responsive design. It features a dark theme with amber accents, smooth animations, and parallax effects.

## Features

- **Hero section** — Full-viewport hero with parallax background and call-to-action buttons
- **About** — Company overview with key stats (500+ clients, 50+ products, 6+ cement brands)
- **Products** — Catalog of construction materials:
  - Sand (M Sand, P Sand, Vanthavaasi Rough/Nice)
  - Blue Metals (3/4 Jalli, O 3/4, 1 1/2, Chips)
  - Cement (Ultra Tech, Coromandel, Maha HD, Zuari, Dalmia, Ramco)
  - Steel (iSteel, ARS, Tirumala — sizes 6mm–40mm)
  - AAC Blocks (4", 6", 8", 9")
  - Weber (AAC Block Paste)
- **Why Choose Us** — Premium quality, fast delivery, best prices, expert support
- **Contact** — Contact form and business information
- **Responsive design** — Mobile-friendly with collapsible navigation
- **Accessibility** — Semantic HTML, ARIA labels, keyboard navigation

## Tech Stack

- HTML5
- CSS3 (custom properties, Grid, Flexbox)
- Vanilla JavaScript
- Google Fonts (Bebas Neue, Inter)

## Project Structure

```
saravanaagencies/
├── images/
│   ├── aac-blocks.jpg
│   ├── blue-metals.jpg
│   ├── cement.jpg
│   ├── hero-bg.jpg
│   ├── sand.jpg
│   └── steel.jpg
├── index.html
├── placeholder.svg
├── robots.txt
└── README.md
```

## Getting Started

1. **Clone or download** the project
2. **Open** `index.html` in a browser

For local development with live reload, use a simple HTTP server:

```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve
```

Then visit `http://localhost:8000`

## Deployment

This is a static site and can be deployed to any web host:

- **GitHub Pages**
- **Netlify**
- **Vercel**
- **AWS S3** + CloudFront
- Any traditional web server (Apache, Nginx)

## Customization

- **Design tokens** — Colors, spacing, and typography are defined in CSS custom properties at the top of the `<style>` block in `index.html`
- **Contact info** — Update the placeholder text in the Contact section (address, phone, email)
- **Form handling** — The contact form currently shows an alert on submit; connect to a backend or form service (e.g., Formspree, Netlify Forms) for production

## License

© 2026 Saravana Agencies. All rights reserved.
