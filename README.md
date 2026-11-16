# VAP Logistics static website

A responsive rebuild of vaplogistics.com using the supplied new logo and locally stored images from the existing website. No Wix runtime, external fonts, package installation or build step is required.

## Preview
Open dist/index.html directly, or serve dist with any static HTTP server. The current Codex preview uses http://127.0.0.1:4173.

## GitHub and Cloudflare Pages
1. Create a GitHub repository and upload the contents of this folder, keeping the dist folder.
2. In Cloudflare, create a Pages project and connect that repository.
3. Framework preset: None. Build command: exit 0. Build output directory: dist.
4. Deploy and check the temporary pages.dev address before changing your domain.
5. Add vaplogistics.com and www.vaplogistics.com through the Pages custom domains panel and follow the displayed DNS instructions.
6. Preserve all email DNS records (MX, SPF, DKIM and DMARC) during DNS migration. Website hosting and email hosting are separate.
7. Check both domain names, HTTPS, phone links and the enquiry flow before ending Wix hosting. Domain registration renewals and email services are separate from static hosting.

Cloudflare docs:
https://developers.cloudflare.com/pages/framework-guides/deploy-anything/
https://developers.cloudflare.com/pages/configuration/custom-domains/

## Editing
Content: dist/index.html
Appearance: dist/styles.css
Navigation and enquiry flow: dist/app.js
Logo and site images: dist/assets/

## Status
Source published to https://github.com/ntngawade/VAPLogistics on the main branch. Ready to connect to Cloudflare Pages. No production domain or Wix configuration has been changed.

Business enquiries open WhatsApp to Vikram Vaje, +91 86003 33148, with the form details. Customers must press Send in WhatsApp; the website does not send or store enquiries itself.

