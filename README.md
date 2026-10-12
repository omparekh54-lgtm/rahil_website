# Global Integrated Solutions

Responsive business website built from the supplied Essence in Form, Offerings, and About Us & CSR design PDFs.

## Pages
- Home: gradient introduction, original iris/perfume artwork, seven-stage process, lavender offerings carousel, contact footer.
- Offerings: five accessible tabs with shareable category URLs.
- About Us and CSR: supplied business and social responsibility copy.
- Contact: email, telephone, Instagram and a direct enquiry submission form.

## Development
No build step or package installation is required. Run `python -m http.server 8000` in this directory.

## Deployment
Import this repository into Vercel with Framework Preset **Other**. Leave the build command empty. The site is static and has no backend or database.

## Enquiries
The contact form submits through FormSubmit to admin@globalis.co.in with all enquiry fields, a table email template, and the visitor’s email as Reply-To. The mailbox owner must click the one-time FormSubmit activation email before notifications are forwarded. The form waits for provider acceptance, blocks duplicate clicks, keeps details on failure, and includes a honeypot. No email credentials are exposed.

## Assets and motion
The original logo and both photographs were extracted from the user-supplied PDFs. Jura is embedded locally (SIL Open Font License). Motion uses IntersectionObserver, CSS transitions, and scroll-linked image transforms, with support for reduced-motion preferences. There are no third-party trackers.
