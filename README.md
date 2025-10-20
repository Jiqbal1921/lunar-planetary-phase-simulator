# Lunar & Planetary Phase Simulator

A zero-dependency, single-page web app to visualize lunar and exoplanet illumination phases and reflected-light phase curves.

## Features
- Real-time disk renderer with Lambertian phase.
- **Moon mode** with date-linked phase and **bright-limb position angle** (PA) via RA/Dec.
- **Exoplanet mode** with inclination, eccentricity, argument of periastron, albedo, and (R_p/a); live **phase-curve**.
- Named **exoplanet presets** with metadata (HD 209458 b, Kepler-10 b, 51 Peg b, WASP-12 b, GJ 1214 b, TOI-700 d, LHS 1140 b, K2-18 b).
- PNG snapshot and CSV export.
- Built-in **self-tests** (see badge and browser console).

## How to run locally
Just open `index.html` in any modern browser.

## Deploy to GitHub Pages
1. Create a new public repo, e.g. `lunar-planetary-phase-simulator`.
2. Add these files at the repo root: `index.html`, `README.md`, `LICENSE`, `.nojekyll`.
3. Push to `main`.
4. In **Settings → Pages**, set **Source** to `Deploy from a branch` and choose `main` / root.
5. Wait a minute; the site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Notes
- This app uses simple approximations (Meeus-style low-order series) for speed. Great for teaching; not a replacement for a full ephemeris.
- Orientation PA is measured from celestial north toward east (approx on-sky convention).

## License
MIT. See `LICENSE`.
