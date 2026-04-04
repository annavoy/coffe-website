# Bean Scene — Coffee Landing Page

A responsive, single-page marketing site for a fictional coffee brand (**Bean Scene**). Built as a portfolio piece to demonstrate semantic HTML, mobile-first layout, and accessible front-end patterns without a framework.

**[Live demo](https://annavoy.github.io/coffe-landing-page/)** · **[Repository](https://github.com/annavoy/coffe-landing-page)**

> **Publish the site (first time):** On GitHub, open **Settings → Pages → Build and deployment**. Under **Source**, choose **Deploy from a branch**, then select branch **`main`** and folder **`/ (root)`**, and save. After a short build, the live demo link above should load. This repo is plain static HTML at the root, so no build step or GitHub Actions workflow is required.

## Overview

The page presents a full landing experience: hero, menu highlights, about, features, testimonials, feedback, newsletter signup, and footer. Navigation uses in-page anchors with smooth scrolling; the layout adapts from phones to large desktops.

## Tech stack

| Layer        | Details                                              |
| ------------ | ---------------------------------------------------- |
| Markup       | HTML5                                                |
| Styling      | CSS3, custom media queries, no preprocessor        |
| Behavior     | Vanilla JavaScript (mobile menu, scroll reveal)    |
| Typography   | Google Fonts (linked in `index.html`)              |

## Features

- **Responsive header** — Desktop nav plus burger menu with overlay, focus management, and **Esc** to close  
- **Section flow** — Hero with CTA, menu, about, features, testimonial, feedback, subscribe, footer  
- **Smooth anchor navigation** — Hash links scroll to section targets  
- **Motion** — Scroll-reveal style treatment for section entrance  
- **Accessibility-minded details** — Focus-visible styles, `aria-*` on the mobile menu, `rel="noopener noreferrer"` on external links  
- **Performance touches** — Lazy-loading on non-critical images  

## Repository structure

```text
coffee-landing-page/
├── index.html
├── css/
│   └── style.css
├── images/
│   └── …
└── README.md
```

The stylesheet is loaded from `./css/style.css` in `index.html`.

## Getting started

### Option A — Open the file

Open `index.html` directly in your browser. This is enough to review layout and static behavior.

### Option B — Local server (recommended)

A simple HTTP server avoids subtle issues with some APIs and paths during development.

**Python 3** (from the project root):

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

**Node.js** (if you use `npx`):

```bash
npx --yes serve .
```

## Responsive breakpoints

Styles are organized around these widths:

| Breakpoint     | Target              |
| -------------- | ------------------- |
| Base           | Mobile-first (`< 768px`) |
| `768px`        | Tablet              |
| `1024px`       | Desktop             |
| `1200px`       | Large desktop       |

## Project highlights

Recent polish includes corrected in-page anchor targets, consistent mobile menu behavior (open, close, overlay, link navigation, Escape), copy and typo fixes, basic `.fade-in` reveal styling, improved small-screen typography, and safer handling of decorative images on narrow viewports.

## Possible next steps

- Replace placeholder copy with final brand or portfolio messaging  
- Wire **Sign In**, **Sign Up**, and primary CTAs to real URLs or forms  
- Add `aria-current="page"` (or similar) for active navigation state  
- Optimize images (compression, WebP/AVIF) and add favicon + Open Graph meta tags  
- Split `style.css` into logical partials or layers if the stylesheet grows  

## License

This project is licensed under the [MIT License](LICENSE).

## Author

Anna Rymarenko
