# Bean Scene Landing Page

Portfolio landing page project for a coffee brand concept.

## About

This is a responsive one-page landing built with:

- HTML5
- CSS3 (custom responsive styles)
- Vanilla JavaScript (scroll reveal + mobile menu)

## Features

- Hero section with CTA
- About, products, features, testimonial, feedback, subscribe, and footer sections
- Responsive navigation with burger/mobile menu
- Smooth scrolling anchor navigation
- Scroll-reveal section animation
- Keyboard-friendly interactions (focus states, `Esc` to close menu)

## Project Structure

```text
website-coffee/
  index.html
  css/
    style.css
  images/
    ...
```

`index.html` uses `css/style.css`.

## Run Locally

1. Open the project folder.
2. Open `index.html` in a browser.
3. For best development workflow, use a local server (for example, VS Code Live Server).

## Responsive Breakpoints

- Mobile: default styles (`< 768px`)
- Tablet: `@media (min-width: 768px)`
- Desktop: `@media (min-width: 1024px)`
- Large desktop: `@media (min-width: 1200px)`

## Improvements Already Applied

- Fixed in-page section anchors for navigation links.
- Added mobile menu behavior (open/close/overlay/Escape/link click).
- Corrected copy and typo issues in multiple sections.
- Added safer external links (`rel="noopener noreferrer"`).
- Added lazy-loading to non-critical images.
- Added basic reveal animation styles for `.fade-in`.
- Improved focus-visible states for better keyboard accessibility.
- Improved small-screen typography and decorative image behavior.

## Suggested Next Improvements

- Replace placeholder `Lorem Ipsum` copy with real portfolio/brand messaging.
- Add real links/actions for `Sign In`, `Sign Up`, and CTA buttons.
- Add `aria-current="page"` logic for active nav state.
- Compress images and provide WebP/AVIF alternatives.
- Split CSS into sections or components for easier maintenance.
- Add favicon and Open Graph meta tags for sharing.

## Author

Anna Marenko

