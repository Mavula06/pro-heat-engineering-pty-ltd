# Pro Heat Engineering & Consulting (Pty) Ltd — Payfast-ready website

This is a professional static website for Pro Heat Engineering & Consulting (Pty) Ltd.

## Included
- Responsive professional homepage
- Services, about, process and contact sections
- Online payment page
- Terms & Conditions
- Privacy Policy
- Refund & Cancellation Policy
- Mobile navigation
- Existing `logo.png` is expected in the project root

## Payfast setup
The `pay.html` page intentionally contains a placeholder instead of merchant credentials.

Payfast's official Pay Now feature lets a merchant generate button HTML from the Payfast dashboard and add it to a website. Generate the button for the correct service/payment amount and paste the supplied HTML into the marked area in `pay.html`.

For a custom integration, keep private merchant credentials and passphrases server-side. Do not commit secrets to GitHub.

## Before Payfast verification
Replace/confirm the following with the company's actual information:
- Registered company number
- Exact legal business name
- Physical/business address
- Customer support email and telephone
- Final service descriptions
- Final refund/cancellation rules
- Any required VAT information
- Any industry registrations, licences or certificates that are actually held

Do not publish information that is not true or cannot be verified.

## Deployment
This site is static and can be hosted on GitHub Pages, Netlify, Cloudflare Pages or another HTTPS host.

For production payments, use HTTPS and the official Payfast-generated button/integration. Test the payment flow before going live.

