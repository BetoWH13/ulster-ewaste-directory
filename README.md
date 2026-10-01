# Ulster E-Waste Directory

Independent, ad-supported directory for electronics recycling, reuse, and disposal options in Ulster County, New York.

## Current build

- Homepage
- 6 verified location pages
- 21 town/city routing pages
- Countywide municipality coverage hub
- 15 item guides
- 3 support guides
- Noindex QA link map
- robots.txt

Directory first. Item guides support the directory. No forms, accounts, API dependency, or claims of affiliation with municipalities, UCRRA, retailers, or recyclers.

## Pre-launch domain tasks

Once the final public domain is chosen:

1. Add absolute canonical URLs.
2. Add absolute `og:url` values.
3. Generate `sitemap.xml` with absolute URLs.
4. Add the sitemap URL to `robots.txt`.
5. Add/validate homepage structured data using absolute URLs.

## CSS architecture

- `assets/accessibility.css` — shared base, layout defaults, focus/skip-link and reduced-motion behavior
- `assets/home.css` — homepage-only presentation
- `assets/content.css` — item guides, support guides and location listings
- `assets/town-guide.css` — municipality hub and town/city routing pages

Page-level `<style>` blocks were removed from the production HTML so future visual changes stay centralized.
