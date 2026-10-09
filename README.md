# Amani House — Hotel Website Demo

A responsive, premium hospitality website concept built with HTML, CSS and vanilla JavaScript. The design is intended to showcase a boutique hotel / safari lodge to prospective clients.

## Features

- Responsive desktop, tablet and mobile layouts.
- Separate desktop MP4 and mobile WebM hero video sources.
- Hero image fallback if video files are missing or unsupported.
- Room and suite cards, experiences, amenities, gallery, journal and contact sections.
- Date and guest selector plus an enquiry modal with client-side validation.
- Accessible navigation toggle, reduced-motion fallback, lazy-loaded imagery and no frontend framework.

## Add the supplied hero videos

Upload the two provided videos to the repository at these exact paths:

- `assets/hotel-hero-desktop-1080p.mp4` — desktop / larger screens
- `assets/hotel-hero-mobile.webm` — mobile screens

The HTML already points to these paths. Until the videos are uploaded, the hero falls back to its background image. The mobile video should be around 4.5 MB; the desktop version is around 7.7 MB. If GitHub's browser upload fails due to file size or connection, use GitHub Desktop or Git from a computer.

## Preview with GitHub Pages

1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then save.
4. Once Pages finishes publishing, open the published URL shown in Settings → Pages.

## Important demo notes

- **Amani House is a fictional concept brand.** Replace the name, copy, imagery and all property details before using this for a real hotel.
- Room categories, experiences and imagery are illustrative and do not represent a real property or verified amenities.
- The enquiry form is a front-end demonstration. It validates inputs and shows a preview, but it does **not** send email or create a reservation. Connect the hotel's real booking engine, email service or backend before production.
- Some gallery imagery is loaded from Unsplash over the internet. For production, use approved/licensed property photography and confirm each asset's usage terms.
- No rates, awards, guest reviews or availability claims have been fabricated into the design.

## Tech

Static HTML · CSS · Vanilla JavaScript
