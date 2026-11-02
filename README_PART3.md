# Moeng Farms — Part 3 implementation and verification

## Features implemented
- Dynamic product listings (data/products.json, mirrored to js/products.js for file compatibility), filtering and sorting.
- Illustrative product prices: fruit R25/kg, vegetables R20/kg, meat R80/kg. These are **not verified business prices**.
- Enquiry form integrates live estimate, validation and AJAX Netlify Forms request.
- Contact form includes message type, HTML5 validation and AJAX Netlify Forms request.
- Gallery lightbox (where gallery images match gallery selectors), scroll reveals and reduced-motion accessibility.
- Descriptions, image alt fallbacks, robots.txt, security headers, sitemap template.

## Deployment steps — required to finish Part 3
1. Confirm real prices, business contact details, social links, and precise physical location(s) with Moeng Farms.
2. Deploy the contents of this folder to Netlify; enable form detection in Netlify settings and redeploy if necessary.
3. Submit both forms on the deployed website and verify each entry in the Netlify dashboard; configure email notifications. Client-side AJAX is not proof of delivery.
4. Replace YOUR-REAL-DOMAIN in sitemap.xml.template with the actual HTTPS site address; rename to sitemap.xml, then add its URL to robots.txt.
5. Verify image licences and attribution; rename generic image filenames and update HTML references.
6. Verify local business details and earn genuine relevant backlinks; publish actual social media posts.
7. Test desktop, tablet and mobile; Chrome, Firefox and Edge; record screenshots and Lighthouse results.
8. Add Part 2 lecturer feedback corrections to the changelog and cite any externally sourced material.

## Changelog
- Part 3: added searchable dynamic product catalogue, estimates, unified quotation form, AJAX submission handling, contact message type, SEO and accessibility improvements.

## Test cases
- 2 kg fruit → R50; 3 kg vegetables → R60; 4 kg meat → R320.
- Quantity 0 or negative should not submit; malformed phone number should show error.
- Search 'fruit' shows fruit; price sort low-to-high lists vegetables, fruit, meat.
- AJAX form submission requires live Netlify hosting and enabled forms.

## Academic integrity
Disclose AI-assisted changes according to the IIE assessment policy and add citations for external assets and borrowed code.

## 2026-10-28: gallery and SEO enhancements
- Fixed Farm & Food and Produce tabs by implementing event handlers and accessible panel toggling.
- Added social sharing controls and local SEO/backlink action plan.
- External backlinks, real social posting and business verification remain pending until real URLs, ownership approval and deployment are available.
