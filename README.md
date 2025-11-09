# Amazon demo (HTML & CSS only)

This is a small static demo of an Amazon-style landing page implemented with only HTML and CSS (no JavaScript).

What I changed

- Fixed malformed stylesheet link and included Font Awesome from CDN.
- Converted navigation to semantic markup (`nav`, `main`, `header`).
- Made the search an accessible `<form>` with a visible label (visually hidden for sighted users) and a proper submit button.
- Replaced decorative `div` background-image boxes with `<img>` elements and `alt` text for better accessibility.
- Added responsive CSS rules and CSS variables for easier tweaking.
- Improved focus styles and keyboard accessibility for interactive controls.

How to view

1. Open `amazon_p1.html` in your browser (double-click or right-click -> Open with...).
2. Resize the browser to see responsive behavior. The search bar collapses on small screens.

Notes & next steps

- Image files referenced (e.g., `amazon_logo.png.jpg`, `back1.png.jpg`) should be present in the same folder. If not available, replace them with your own images or remove the `src` attributes.
- If you'd like, I can further refine responsive breakpoints, add better alt text, or provide multiple image sizes for performance.
- Added product metadata (price + short description) and switched product layout to CSS Grid for responsive behavior.

Enjoy! If you'd like additional design or content changes (e.g., more categories, editorial banners, or a mobile-first redesign), tell me what to focus on next.