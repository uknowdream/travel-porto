# NusaTrip — Travel & Tourism Portfolio

NusaTrip is a responsive, Indonesian-language travel website concept showcasing destinations and curated trip packages.

## Features
- Responsive navigation for desktop and mobile, with accessible menu state
- Destination and trip-style filtering
- Favorite destinations persisted in browser storage when available
- Reduced-motion-aware scrolling and accessible status messages
- Responsive destination and package cards with lazy-loaded imagery
- SEO description, robots metadata, and Open Graph metadata
- Dependency-free HTML, CSS, and vanilla JavaScript

## Run locally
Open `index.html` in a modern browser. Google Fonts and Unsplash images require an internet connection.

## Quality checks
Requires Node.js 20 or newer. Run:

```sh
npm test
```

The test suite checks HTML essentials, image alternatives, required controls, metadata, and JavaScript syntax. It is a lightweight static check, not a replacement for browser-based end-to-end or accessibility testing.

## Demo limitations
This is a fictional portfolio/demo project, not a live travel agency. Prices, reviews, testimonials, and statistics are illustrative and must be verified or replaced before commercial use.

No backend, database, customer accounts, booking engine, payment gateway, email delivery, CRM, or admin dashboard is connected. The search and favorite features run in the browser; favorites depend on browser storage availability. Newsletter and package inquiry actions explicitly remain demo-only.

## Deployment
The site is static and can be hosted on GitHub Pages, Vercel, or another static host. Configure the host to serve the repository root; no build command or output directory is required. A production deployment has not been verified by this repository's code changes alone.

## Tech stack
HTML5 · CSS3 · Vanilla JavaScript · Node.js built-in test tooling

## License
Portfolio/demo project. Review content, image licensing, privacy requirements, and business integrations before production use.
