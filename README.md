# KA-Launchly

KA-Launchly is a premium multi-page Startup & SaaS Website Template built with HTML5, TailwindCSS and Vanilla JavaScript.

## Highlights

- 30+ polished pages for startup, SaaS, AI and software product websites
- Dark and light mode support
- Sticky glassmorphism navbar and premium card system
- Reusable UI kit with buttons, pricing tables, tabs, dropdowns, accordion, modal and form patterns
- Blog, docs, auth, company and utility pages included
- Minimal JavaScript for reveal animations, theme toggle, tabs, accordion, dropdowns, modals and dashboard charts

## Tech Stack

- HTML5
- TailwindCSS via CDN
- Vanilla JavaScript
- Optional vendors loaded via CDN:
  - Chart.js
  - Swiper.js

## Build / Regenerate

```bash
node scripts/build-site.mjs
```

## File Structure

```text
/assets
  /css
  /img
  /js
/components
/pages
  /auth
  /blog
  /docs
/scripts
index.html
README.md
```

## Pages

### Landing

- `index.html` - Home Landing
- `pages/saas-landing.html` - SaaS Landing
- `pages/startup-landing.html` - Startup Landing
- `pages/ai-product-landing.html` - AI Product Landing
- `pages/mobile-app-landing.html` - Mobile App Landing

### Product

- `pages/features.html` - Features Page
- `pages/product-overview.html` - Product Overview
- `pages/integrations.html` - Integrations Page
- `pages/use-cases.html` - Use Cases Page
- `pages/roadmap.html` - Roadmap Page
- `pages/dashboard.html` - Dashboard Demo

### Pricing

- `pages/pricing.html` - Pricing Page
- `pages/pricing-comparison.html` - Pricing Comparison
- `pages/pricing-faq.html` - Pricing FAQ

### Blog

- `pages/blog/list.html` - Blog List
- `pages/blog/grid.html` - Blog Grid
- `pages/blog/article.html` - Blog Article

### Docs

- `pages/docs/index.html` - Docs Home
- `pages/docs/getting-started.html` - Getting Started
- `pages/docs/api-documentation.html` - API Documentation
- `pages/docs/changelog.html` - Changelog

### Auth

- `pages/auth/login.html` - Login
- `pages/auth/register.html` - Register
- `pages/auth/forgot-password.html` - Forgot Password
- `pages/auth/reset-password.html` - Reset Password

### Company

- `pages/about.html` - About
- `pages/careers.html` - Careers
- `pages/contact.html` - Contact
- `pages/support.html` - Support

### Utility

- `pages/404.html` - 404 Page
- `pages/maintenance.html` - Maintenance Page
- `components/ui-kit.html` - UI Kit

## Notes

- Replace logos, copy, metadata and contact details with your own brand data.
- TailwindCSS is loaded from CDN for easy editing. You can replace this with a local build later if desired.
- The dashboard demo is intentionally lightweight so the startup website remains the main focus.
