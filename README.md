# Aradhya — Engineering & Business Portfolio

A single-page personal portfolio with two sides: **Engineering** and **Business & Leadership**. Hosted on GitHub Pages.

**Live site:** `https://<your-username>.github.io/aradhya-portfolio/`

## What's inside

**Engineering projects**
- **VEX Robotics** (Team 81Z Zephyr): the 10-robot iteration timeline, the design areas, CAD and awards
- **Environmental Engineering**: hydrogel and soil research
- **S.N.A.K.E. (VeinAssist)**, *in progress*: a non-invasive robot that maps forearm veins with near-infrared light and rotates IV access sites
- **Head-Tracked FPV RC Car**, *in progress*: a pan/tilt camera gimbal that follows the driver's head over ESP-NOW

**Business & Leadership**
- DECA and FBLA competition results
- HOSA and student government
- Volunteering and mentoring

**Resume** is included as a PDF (`resume.pdf`).

## Files

```
index.html               The whole site: markup, styles and logic
support.js               Runtime the page needs to render
image-slots.state.json   Saved crop and position for each photo spot
resume.pdf               Downloadable resume
assets/                  Photos, CAD screenshots and drawings (.jpg / .png / .webp)
```

## Running it locally

The page loads its files over HTTP, so opening it by double-clicking won't work. Serve the folder instead:

```bash
cd aradhya-portfolio
python3 -m http.server 8000
# open http://localhost:8000
```

## Updating the site

1. Edit or replace files in the repo. New images go in `assets/`.
2. Commit to the `main` branch.
3. Wait 1–2 minutes for GitHub Pages to rebuild, then hard-refresh (or open an incognito window).

**Adding or swapping a photo:** put the file in `assets/` and point the matching `src="assets/..."` in `index.html` at it. File names are case-sensitive on GitHub Pages.

## Deployment

The site is published with GitHub Pages using **Settings → Pages → Deploy from branch → `main` / root**.

## Notes

- **S.N.A.K.E.** is pending a provisional patent. Keep detailed design information (scoring formulas, weights) off the public site until the patent is filed.
- There's no build step and no dependencies to install. It's plain static files.

## Contact

Aradhya: see the contact section on the site or the resume.

© 2026 Aradhya. All rights reserved.
