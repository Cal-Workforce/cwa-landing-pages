# CWA Landing Pages

Standalone, single-file landing pages for the **California Workforce Association**.
Each page is self-contained (CSS/JS inline, assets inlined or in `assets/`) with no
build step. Deployed as static files (see `netlify.toml`).

## Pages

- `executive-fellowship.html` — landing page for the **CWA Executive Fellowship**, the
  year-long leadership program for workforce development executives.
- `webinars.html` — registration landing page for the **California AI Blueprint Design
  Session** webinar (CWA brand; registration CTAs link to Zoom).

## Executive Fellowship — placeholders to replace before launch

Search `executive-fellowship.html` for these HTML comments:

- `<!-- VERIFY BIO -->` — draft bios for Adam Peck and Tim Aldinger.
- `<!-- PLACEHOLDER TESTIMONIAL -->` — alumni quotes.
- `<!-- PLACEHOLDER ALUMNI -->` — 2026 cohort names/titles.
- `<!-- PLACEHOLDER FORM: connect to CWA's form/CRM -->` — the application form is non-functional.
- `[DATE — CWA to confirm]` — application open date (appears twice).
- `fellowship@calworkforce.org` — contact email placeholder.
- Footer links (`CWA Home`, `Contact`, `Privacy`) point to `#`.
