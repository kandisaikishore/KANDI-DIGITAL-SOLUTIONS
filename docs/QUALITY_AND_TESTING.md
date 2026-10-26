# Static Website Development and QA Guide

This repository contains a static `index.html` entry point for Kandi Digital Solutions. Review the current HTML and assets before assuming there is a backend or additional framework.

## Run locally

```bash
git clone https://github.com/kandisaikishore/KANDI-DIGITAL-SOLUTIONS.git
cd KANDI-DIGITAL-SOLUTIONS
```

Open `index.html` in a modern browser. A repository URL is not a live deployment URL; only publish a public demo link after verifying the deployment.

## Content and accessibility checks

- Confirm page title, description, language declaration, and heading order.
- Check that all local images, fonts, scripts, and stylesheets load.
- Give informative images useful alt text and decorative images empty alt text.
- Ensure links and controls have meaningful names and visible keyboard focus.
- Verify text contrast, zoom behavior, and layouts at mobile/tablet/desktop widths.
- Check contact details and service claims for accuracy.

## Link and asset validation

Before submitting changes, inspect local references and internal links for missing files. Test contact links by verifying their target and format; do not claim a message was delivered if the page only opens an email client.

## Pull-request checklist

- [ ] Open the page in a browser and test the changed section.
- [ ] Check local assets, internal links, and console errors.
- [ ] Verify keyboard navigation and responsive layout.
- [ ] Preserve existing content unless a specific defect requires a change.
- [ ] State any checks that were manual or unavailable.
