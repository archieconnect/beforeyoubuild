# Before You Build — Website

Static marketing site for **Before You Build**, a customer research consultancy founded by Archie (Archana Hublikar).

## What it is

Before You Build offers embedded UX research on a flexible retainer — sector-neutral, senior-led, typically 3+ month engagements. The site positions Archie as a thought partner for product and business leaders, not a one-off research vendor.

## Stack

Plain HTML/CSS/JS. No framework, no build step, no dependencies beyond Google Fonts. Each file is self-contained and deploys as-is.

## File map

| File | Purpose |
|------|---------|
| `index.html` | Main homepage |
| `beforeyoubuild-case-fintech-onboarding.html` | Case study: Fintech · Onboarding |
| `beforeyoubuild-case-fintech-investment-dashboard.html` | Case study: Fintech · Investment Dashboard |
| `beforeyoubuild-case-retail-checkout.html` | Case study: Retail · Checkout |
| `beforeyoubuild-case-retail-inspiration-hub.html` | Case study: Retail · Inspiration Hub |
| `beforeyoubuild-case-retail-loyalty.html` | Case study: Retail · Loyalty |
| `beforeyoubuild-case-retail-stylist-tool.html` | Case study: Retail · Stylist Tool |
| `beforeyoubuild-case-travel-package-booking.html` | Case study: Travel · Package Booking |
| `beforeyoubuild-case-travel-resort-bookings.html` | Case study: Travel · Resort Bookings |
| `beforeyoubuild-case-travel.html` | Redirect → package booking case study |
| `beforeyoubuild-case-hospitality-ryokan.html` | Case study: Hospitality · Ryokan |
| `beforeyoubuild-case-realestate-benchmarking.html` | Case study: Real Estate · Benchmarking |
| `beforeyoubuild-case-realestate-portfolio.html` | Case study: Real Estate · Portfolio |
| `beforeyoubuild-case-research-prioritization.html` | Case study: Methodology · Research Prioritization |
| `beforeyoubuild-case-booking.html` | Redirect → package booking case study |
| `squarespace-custom-css.txt` | Custom CSS snippet for Squarespace injection |
| `images/` | All image assets |

## Homepage sections

1. **Hero** — headline, sub-headline, engagement model line, CTA buttons
2. **Problem** — why research-first product work matters
3. **Services (Zones)** — four engagement modes with "This is for you if" prompts
4. **Work** — case study card carousel (12 cards, filterable by sector)
5. **About** — founder bio, credentials, career stats
6. **Testimonials**
7. **Comparison table** — embedded vs agency vs DIY
8. **Contact** — contact form with AJAX submit

## Conventions

- Do not add pricing to the site
- Keep copy sector-neutral unless building a sector-specific variant
- Do not delete case study files — redirect if a URL needs to change
- Images go in `images/` relative to the HTML files
- "Archie" in casual/site copy; "Archana" in formal/legal contexts

## Deployment

Targeting **beforeyoubuild.ca** (or userlens.ca — TBC). Static files only — drop onto any host (Netlify, GitHub Pages, S3, etc.).

<!-- test update 2026-03-28 -->
