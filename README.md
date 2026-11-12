# Eros Photography

Wedding, elopement, and engagement photography serving the Rio Grande Valley and destination celebrations. Part of the [MetaLumina](https://metalumina.studio/) spectrum.

**Website:** [erosphotos.com](https://erosphotos.com/)

## About the site

A streamlined, mobile-friendly inquiry funnel built on the **Strada** BootstrapMade template. The single-page experience includes:

- **Hero:** Photography-led introduction and inquiry CTA
- **Our Approach:** Candid storytelling and photographic style
- **Services:** Weddings, elopements, and engagements, with coverage highlights
- **What to Expect:** A simple overview of planning, photography, and delivery
- **Inquire:** Email-first contact form with flexible event dates and venue details

## Technology

- HTML5, CSS3, Bootstrap 5, and vanilla JavaScript
- BootstrapMade **Strada** template (commercial license)
- Static hosting via **GitHub Pages**, with the `erosphotos.com` custom domain
- **Formspark** for inquiries, with inline success/error feedback, a honeypot field, and duplicate-submission prevention
- **Google Analytics 4:** `G-ZXQ3X0J7ZV`
- Canonical URL, Open Graph/Twitter metadata, and `ProfessionalService` JSON-LD

## Key files

```text
index.html              Page content, metadata, inquiry form
assets/css/main.css     Eros brand styling and responsive layouts
assets/js/main.js       Navigation and Formspark form behavior
assets/img/             Logos and photography assets
assets/vendor/          Bootstrap and template dependencies
```

The inquiry form posts to **`https://submit-form.com/u8jpLyqLk`** and captures the visitor’s email address for follow-up. Inquiries can also be sent directly to **book@erosphotos.com**. Calls are arranged individually after email contact, rather than through public calendar scheduling.

Featured page assets include `goldenHour.png` (hero), `sunsetSolace.png` (What to Expect), `hug.jpg` (Our Approach), and `juxtaposedHands.jpg` (inquiry sidebar). Images are referenced from `assets/img/`; keep filenames and extensions consistent with `index.html`.

## Maintenance

Update the page copy and image paths in `index.html`, visual styling in `assets/css/main.css`, and form/navigation logic in `assets/js/main.js`. Retain the vendor directory and test the inquiry form on the live site after deployment.
