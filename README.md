# blog.html - Amazon Blog/Ecommerce Page

## Overview
This is a single-page static HTML file implementing an Amazon-styled blog or product showcase page. It features a modern ecommerce layout with hero section, product grids, shopping cart drawer, and navigation. The design uses Tailwind CSS for styling and Tailwind Elements for interactive components like the shopping drawer.

## Features
- **Navigation Bar**: Logo (Amazon-like), links to Home, Blog (current), and Contact.
- **Hero Section**: Prominent heading "Summer styles are finally here" with product image grid and CTA "Shop Collection".
- **Related Products Grid**: 4 product cards with images, names (e.g., Basic Tee), colors, and prices.
- **Product Catalog**: 8 product cards (e.g., Earthen Bottle, Nomad Tumbler) with images, names, and prices.
- **Interactive Shopping Cart**: Drawer modal triggered by "Open drawer" button, showing cart items (Throwback Hip Bag, etc.), subtotal, and checkout.
- **Footer**: Copyright, links (About, Privacy Policy, Licensing, Contact).

## Technologies Used
- **HTML5** with semantic structure.
- **Tailwind CSS v4** (loaded via CDN: `https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4`).
- **Tailwind Elements** (uncomment script for full interactivity: `<script src="https://cdn.jsdelivr.net/npm/@tailwindplus/elements@1" type="module"></script>`).
- External images from Tailwind CSS demo assets.

## Images
- Amazon logo: Base64-encoded inline PNG.
- Products: Hosted on `https://tailwindcss.com/plus-assets/img/ecommerce-images/` (hero tiles, product cards, cart items).

## Navigation Integration
- Home: `index.html`
- Blog: `blog.html` (self)
- Contact: `contact.html` (external, not in cwd)

## How to Run/Preview
1. Open `blog.html` directly in any modern web browser (e.g., Chrome, Firefox).
2. No build step required – fully static.
3. Click "Open drawer" to test shopping cart modal.
4. Responsive design works on mobile/desktop.

## File Structure Context
Part of a training project with sibling files: `index.html`, `advancecss.html`, `tailwind.html`, `portfolio.html`.

## Potential Improvements
- Add `contact.html`.
- Replace demo images with custom assets.
- Uncomment Tailwind Elements script for production.
- Host externally for better performance.
- Add meta tags for SEO (description, keywords).
