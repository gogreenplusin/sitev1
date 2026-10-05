# GoGreen+ website redesign — v2

Open `index.html` in any modern browser (double-click it). Every page lives in that one file; it loads photos, fonts and documents from the `assets` folder next to it, so keep the two together.

v2 keeps the v1 visual direction and applies the review feedback: only the existing site's words and specifications, a calmer type scale, a new navigation, viewport-fitted heroes, tighter spacing and right-sized images, and soft animated background shapes.

## What's inside

| Path | Contents |
| --- | --- |
| `index.html` | The complete site: all pages, styles and scripts in one file |
| `assets/img/` | The same brand, product, place and team images as v1 (no new images) |
| `assets/fonts/` | Manrope variable font (Latin + Latin Extended) |
| `assets/docs/` | Brochure, start-up recognition certificate, Udyam registration |
| `page-renders/desktop/` | Full-page images of every page at 1440 px, plus both menus open |
| `page-renders/mobile/` | Full-page images of every page at 390 px (2× resolution), plus the menu open |

## Pages

Home · Products & services · six product pages (specifications, How It Works, brochure tables for VAYU and SegreGO) · three in-development pages · Corporate responsibility · Community impact · About and team · team profiles · Careers (job search, internships, events, working here, our process) · Schedule a pickup · Log in · Page not found.

Community impact, Working here and Our process show the current site's "We're Developing Something Awesome" page, as they do today.

Links from the current site (`#/product-and-services`, `#/corporate-responsibility`, `#/community-impact`, `#/careers/students/internships`, `#/product/<id>` …) open the matching page.

## What changed from v1

- **Content**: every heading, description, specification and bio is the existing site copy. VAYU and SegreGO technical tables are taken word for word from the company brochure.
- **Type**: Manrope replaces Archivo. Headlines are smaller and lighter (max 56 px), body text is 16 px with 1.7 line height.
- **Navigation**: floating glass capsule with a sliding highlight, a Services mega menu (available solutions + in development), a Careers dropdown, a scroll-progress line and a full-screen mobile menu. It narrows slightly as you scroll.
- **Heroes**: every page hero fits in one screen down to 1366 × 768, with clear space under the navigation.
- **Spacing and images**: shorter section padding, no sticky scroll sections, images capped by screen height, spec tables split into two columns, swipeable rows on mobile instead of long stacks.
- **Background**: blurred colour fields and low-opacity line drawings (leaf, rings, recycling loop, contour lines) drift slowly behind sections. Motion is switched off for visitors who ask their system for reduced motion.

## Before going live

- **Job listings and events** are the current site's sample data (company "GoGreen Energy", 2025 dates) — replace them with real openings.
- **Schedule a pickup** and **Apply Now** open the visitor's email app with the details filled in. Wire them to the booking API when this is ported into the React app.
- **Log in** is a design only; it does not connect to the portal.
- Two in-development images (Waste-to-Fuel, Road Water Spray) and Tuhin Paul's photo come from screenshots and are low resolution — swap in originals.
