# Rigel × EPGT website

A responsive, buildless website with English, French and Arabic (RTL), solution exploration tabs, a three-part guided introduction, research accordions, an enquiry composer, and policy information dialogs.

## Open locally
Open dist/index.html in a modern browser. All fonts, photos, logos, styles and scripts are included locally. For development, serve dist with any static HTTP server.

## Files
- dist/index.html — page structure and English content
- dist/styles.css — design, responsive layouts and motion preferences
- dist/app.js — translations and interactions
- dist/assets — supplied logos, optimized photographs and locally hosted fonts
- dist/catalogue.js — product information and expanded About translations

## Contact
No official recipient email was supplied. The enquiry form validates and prepares a downloadable or copyable message. It does not send email or claim delivery. Connect a verified recipient and a real delivery service before enabling direct message submission.

## Content
Partnership and company positioning follow the supplied brief. The website does not invent product names, approval statuses, clinical results or development milestones. Request current product availability and pipeline details from the official team. Website policy dialogs describe this website's current behaviour and are not represented as a verified corporate legal policy.

## Verification
Tested in Chromium at 320, 390, 768, 1024 and 1440 pixels for all three languages. Verified category tabs and keyboard controls, tour navigation, enquiry validation/download, mobile navigation, policy dialogs and language persistence. No JavaScript errors, failed resource requests, visible broken images or horizontal overflow were found.
## Catalogue and expanded About section
The About section now includes two illustrated story sections: the veterinary research perspective and the Middle East partnership. The product catalogue features SEL-E.D3, V-Plex A.D3.E and APRA-TIL with the original supplied package photographs. Each card opens a translated product dialog covering a concise pack-based overview, named ingredients, labelled target species, and an EPGT enquiry action that carries the product name into the contact form.

The catalogue data and added story translations are maintained in dist/catalogue.js. No dosage, concentration, registration status, clinical result or withdrawal period has been inferred from the photographs. Request the official product technical sheet for those details.

## Hosting
This repository contains a static website and requires no build step. Configure your static hosting provider to serve the dist directory. No API keys or hosting credentials are required to preview it.

## Vercel deployment
The root vercel.json configures this buildless HTML website to publish dist, with no install or build command. Import this repository with the repository root as Root Directory. Pushes to main trigger the connected production deployment.
