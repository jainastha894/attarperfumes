# Arjan Attars Website

Static marketing site for Arjanmal Attarchand that highlights signature attars, oils, and heritage. The site is fully static—built with HTML, Tailwind via CDN, and lightweight custom CSS—so it can be opened directly in a browser.

## Page map
- `index.html`: Hero, featured products, testimonials, and brand highlights.
- `shop.html`: Product cards with CTA buttons (front-end only).
- `about.html`: Brand story, craft process, and values.
- `heritage.html`: Timeline of key milestones.
- `contact.html`: Contact form layout and location info.
- `map.html`: Embedded location map helper page.

## Assets
- `public/styles/`: Page-specific CSS (e.g., `home.css`).
- `public/images/`: Product/hero imagery and `favicon.ico`.

## Run locally
- No tooling required—open `index.html` in your browser.
- Tailwind is loaded from a CDN; internet access is needed for those styles.

## Editing tips
- Keep JSON-LD blocks valid (objects inside arrays need braces) to preserve SEO.
- Forms and cart buttons are presentational only; wiring them to a backend requires additional work.
- Update copy, imagery, or CSS directly in `public/images` and `public/styles` as needed.
