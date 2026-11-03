# Codevora Labs Website

A responsive, one-page static website for **Codevora Labs**, an independent, growing software development studio.

**Tagline:** Building Useful Software. Solving Real Problems.

## Tech stack

- HTML5
- CSS3 (custom properties, grid, flexbox)
- Vanilla JavaScript (no frameworks, no build step)
- Google Fonts (Inter)

## Project structure

```
codevora-labs-website/
├── index.html            # All page sections
├── css/
│   ├── style.css         # Colours, typography, layout, components
│   └── responsive.css    # Tablet / mobile breakpoints
├── js/
│   └── main.js           # Mobile menu, scroll animations, active nav link
├── assets/
│   ├── images/           # Company logo (PNG), favicon, hero background (SVG)
│   └── icons/            # Service icons (SVG)
└── README.md
```

## Sections

Home, About Us, Mission & Vision, What We Build, Our Approach, Why Codevora Labs, Let's Work Together (contact), Footer.

## Run locally

Open `index.html` in a browser, or in VS Code install the **Live Server** extension, right-click `index.html` and choose **Open with Live Server**.

## Things to customise

1. **Contact details** — search `index.html` for `hello.codevoralabs@gmail.com`, `linkedin.com/company/codevora-labs` and `github.com/hellocodevoralabs-alt` and replace them with your real links.
2. **Logo** — the provided company logo is used in the navigation, hero, footer and as the favicon at `assets/images/codevora-logo.png`.
3. **Favicon** — the browser tab uses the company logo PNG.
4. **Colours** — edit the variables at the top of `css/style.css` (`:root`).

## Colour palette

| Use | Colour |
| --- | --- |
| Primary background | `#050B1B` |
| Secondary background | `#0B1530` |
| Primary accent | `#168BFF` |
| Secondary accent | `#8052FF` |
| Main text | `#FFFFFF` |
| Secondary text | `#AAB5C8` |

## Deploy to GitHub Pages

1. Push the folder to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your site will be live at `https://<username>.github.io/<repository>/`.

## Licence

© Codevora Labs. All rights reserved.
