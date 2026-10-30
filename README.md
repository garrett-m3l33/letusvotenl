# Let Us Vote NL — website mockup

Interactive, multi-page mockup of the Let Us Vote NL campaign website, built from the
October 2026 design and development brief and the brand identity guidelines.

**This is a demonstration.** Nothing on the site collects, stores or processes real
petition signatures, donations or registrations. Every form, counter and article is
labelled as simulated or sample content.

## Viewing it

Open `index.html` in any browser. No build step, no server, no dependencies beyond the
Google Fonts request for Archivo Black and Inter. If GitHub Pages is enabled for this
repository, the site is served from the root.

## What's here

| Path | Purpose |
|---|---|
| `index.html` | The whole site: shared design system, all thirteen routed pages, and the simulated petition, donation, volunteer and newsletter flows |
| `logos-outlined/` | The five brand masters with the wordmark converted to outlines (see brand notes) |

## Pages

Home · The Issue · The Campaign · Take Action · Sign the Online Petition · Donate ·
Public Accountability · News & Updates · About · Volunteer · Events ·
The People's Vote (future module stub) · Legal & Privacy

Navigation uses URL hashes (`#petition`, `#donate`, `#issue` …) so any page can be
linked directly.

## For production development

The mockup separates what is simulated from what needs backend services: payment
processing, petition verification email, data storage, the CMS, and legal review of
policy text and contributor disclosure. Section 14 of the design brief sets out the
intended production architecture.
