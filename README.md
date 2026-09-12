# Latimer Service Plumbing

Static, single-file landing page for **Latimer Service Plumbing** — serving Saucier &amp; Harrison County, Mississippi.

## Overview

A mobile-first one-pager built around a single conversion goal: getting a visitor to **tap to call** `(228) 669-4036`.

**Features**
- Sticky bottom call-to-action bar optimized for mobile thumbs
- `tel:` links so the phone number dials directly on tap
- Services list (emergency repairs, drain cleaning, water heaters, fixtures)
- Social proof block with a local testimonial
- No build step, no dependencies — one `index.html`

## Project Structure

```
.
├── index.html    # The entire site (markup + inline styles)
└── README.md
```

## Local Development

Any static file server works. For example:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

Or just open `index.html` directly in a browser.

## Deployment

Hosted on Vercel as a static site. Because the entry point is `index.html` at the repo root, no framework preset or build command is required — deploy the repo as-is.

## Notes

- The testimonial in the "Why Choose Us" section is illustrative placeholder copy and should be replaced with a real, attributable review before this page is used publicly.
- The footer currently reads **© 2026**.
