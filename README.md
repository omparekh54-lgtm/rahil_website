# Global Integrated Solutions

Responsive business website built from the supplied Essence in Form, Offerings, and About Us & CSR design PDFs.

## Pages
- Home: gradient introduction, original iris/perfume artwork, seven-stage process, lavender offerings carousel, contact footer.
- Offerings: five accessible tabs with shareable category URLs.
- About Us and CSR: supplied business and social responsibility copy.
- Contact: email, telephone, Instagram and an enquiry draft form.

## Development
No build step or package installation is required. Run `python -m http.server 8000` in this directory.

## Deployment
Import this repository into Vercel with Framework Preset **Other**. Leave the build command empty. The site is static and has no backend or database.

## Enquiries
The contact form prepares a draft in the visitor's email client; it does not claim that an enquiry has been sent. A transactional email backend can be added later.

## Assets and motion
The original logo and both photographs were extracted from the user-supplied PDFs. Jura is embedded locally (SIL Open Font License). Motion uses IntersectionObserver, CSS transitions, and scroll-linked image transforms, with support for reduced-motion preferences. There are no third-party trackers.
