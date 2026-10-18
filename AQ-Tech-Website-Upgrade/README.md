# AQ Tech — Modernized static website

A lightweight, responsive static website for **aqtech.shop**, designed for GitHub Pages.

## Deployment

1. Make a backup of the existing **AQ-Tech** repository before replacing anything.
2. Download this package, extract it, and copy the **contents of the aqtech-site folder** to your GitHub repository root. Do not upload the ZIP itself for GitHub Pages to extract — GitHub Pages does not unzip it automatically.
3. Keep `index.html`, `CNAME`, `sitemap.xml`, `robots.txt`, `assets/`, and each page folder at the repository root.
4. In GitHub repository **Settings → Pages**, publish the root folder on the correct branch if using branch deployment.
5. The `CNAME` file points to `aqtech.shop`. Keep the current GitHub Pages DNS records in your domain registrar. Do not change DNS without confirming its existing configuration.
6. When deployment is finished, check `https://aqtech.shop/` and every navigation link, then submit `https://aqtech.shop/sitemap.xml` to Google Search Console.

## Important business verification (before going live)

- **Package prices:** The displayed prices are copied from previously published content and labeled historical. Verify current pricing, exact products, cable quantities and warranty terms before presenting them as confirmed offers.
- **Contact:** The main contact is 0306-2142514 / WhatsApp `923062142514` and `aq.cctvtech@gmail.com`. Confirm these are still the company's authorized customer channels.
- **Services:** Confirm that AQ Tech currently delivers every listed service, especially regulated safety/electrical installations.
- **Location:** Only Lahore is listed because no full street address was supplied.
- **Team:** Four names and roles have been carried forward from AQ Tech’s existing public website. Verify that the information is still accurate before publication. No fabricated testimonials, certifications or project photos have been added.

## How contact requests work

The Contact form uses browser-side JavaScript to open WhatsApp with a prepared message; it does **not** transmit to a backend and will **not** silently deliver an inquiry. Customers must press Send in WhatsApp. Telephone and email are also directly linked.

## Technical notes

- HTML, CSS, vanilla JavaScript; no npm dependencies, CDNs, external web fonts or remote images.
- Accessible navigation, mobile menu, headings, real form labels, keyboard focus styles and motion preferences.
- Local schema JSON-LD for LocalBusiness and service pages, canonical URLs, Open Graph, sitemap and robots.txt.
- Lightweight local SVG illustrations and favicon.
- `assets/style.css` controls styling and `assets/site.js` handles mobile navigation, package tabs and WhatsApp inquiry preparation.
- Static hosting alone cannot provide server security headers, full form processing, or vulnerability guarantees. Verify deployment and transport behavior separately.

## Suggested later upgrades

Add verified installation photographs/case studies, genuine customer reviews (with permission), actual package equipment makes/models, supported service area details, and a backend form or CRM only when genuinely needed.
