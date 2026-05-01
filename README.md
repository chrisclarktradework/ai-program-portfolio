# ai-program-portfolio

Live HTML demos for the Chris Clark AI program leadership brief.

Public URL once published:
- Landing: https://chrisclarktradework.github.io/ai-program-portfolio/
- Spyglass operations: https://chrisclarktradework.github.io/ai-program-portfolio/spyglass.html
- Spyglass PPM: https://chrisclarktradework.github.io/ai-program-portfolio/ppm.html

Deep links to specific tabs:
- spyglass.html#overview
- spyglass.html#kpis
- spyglass.html#scenarios
- ppm.html#overview
- ppm.html#evm
- ppm.html#steerco/raid
- ppm.html#steerco/roi

## How to publish on GitHub Pages

1. Sign in at github.com as `chrisclarktradework`. Enable two factor auth at github.com/settings/security if you have not done so. The deadline is June 4, 2026.
2. Create a new public repo named `ai-program-portfolio`. No template, no readme on creation.
3. On your computer drag the four files in this folder (`index.html`, `spyglass.html`, `ppm.html`, `README.md`) into the new empty repo page in the browser. GitHub will offer to commit them directly.
4. Open repo Settings, click Pages on the left.
5. Under Build and deployment, source is `Deploy from a branch`. Branch is `main` and folder is `/ (root)`. Save.
6. Wait two minutes. The Pages page will show your live URL: https://chrisclarktradework.github.io/ai-program-portfolio/
7. Open the URL to verify. The landing page lists both demos.

## Files

- index.html: simple landing page with two cards linking to the demos.
- spyglass.html: Byrne Spyglass Supply Chain Control Tower (V2.1). Twelve interactive tabs.
- ppm.html: Byrne Spyglass PPM Control Tower (V1.0). Seven tabs covering spend, burn, EVM, sprints, KPIs and SteerCo (status, RAID, weekly, actions, ROI).
- README.md: this file.

## Notes

- All data is illustrative. Pricing tables show methodology, not actual vendor numbers.
- Charts on the PPM dashboard use Chart.js loaded from cdn.jsdelivr.net.
- No build step. Pure static HTML, CSS and JS.
