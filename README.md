# Pricing Page
 
A responsive SaaS pricing page built with plain HTML and CSS, no frameworks. Three-tier pricing cards, a sticky nav with an active-state indicator, hover interactions, and a footer — all styled from scratch.
 
**Live demo:** https://snehafincy09.github.io/pricing-page/
 
## What it includes
 
- Three pricing tiers (Standard, Premium, Enterprise) with a hover tooltip on each card showing who it's best suited for
- A nav bar with dropdown carets and an active-page indicator
- Custom checkmark list styling using CSS pseudo-elements instead of default bullets
- Hover micro-interactions on cards and buttons (scale, shadow, smooth transitions)
- Fully responsive layout with media queries for tablet and mobile breakpoints
## What I practiced
 
This was a deliberate exercise in flexbox after finishing freeCodeCamp's Responsive Web Design section. Specifically:
 
- Flexbox at two levels — arranging the row of cards, and arranging content inside each card
- `::before` / `::after` pseudo-elements for decorative content (checkmarks, hover labels) without adding extra HTML
- The `attr()` CSS function to pull custom label text from `data-*` attributes
- Transitions and `transform: scale()` for hover effects
- Media query ordering and the cascade — learned the hard way that breakpoints need to go from largest to smallest, or overrides apply in the wrong order
- Semantic HTML — `<article>` for each self-contained pricing card, `<section>` for groupings
## Built with
 
- HTML5
- CSS3 (Flexbox, custom properties, media queries)
- Google Fonts (Inter, Work Sans)
## Notes
 
This is a practice/portfolio project, not a production app — the pricing tiers, copy, and "Flowdesk" branding are fictional, created to practice building a realistic SaaS page layout.
