# EMF Aware + EMC Studio

Dual-mode web app: **Awareness mode** (habit dashboard, distance visualizer, sleep/habit tracker, standards explorer) and **Technical EMC mode** (RF field solver, shielding engine, unit matrix, CISPR 32 / FCC 15 limits check).
Plain HTML, CSS and JavaScript: no build step, no dependencies.

## Files
| File | Purpose |
|---|---|
| `index.html` | Page shell, header mode toggle, bottom navigation |
| `style.css` | Theme tokens (light/dark, Awareness teal, Technical blue) and layout |
| `app.js` | Physics formulas, all screens, navigation, saved history |

## Run in VS Code
Open the folder, install the **Live Server** extension, right-click `index.html` and choose *Open with Live Server*.
Or from a terminal: `python -m http.server 8000` and visit http://localhost:8000

## Push to GitHub and host free
```bash
git init
git add .
git commit -m "EMF Aware + EMC Studio"
git branch -M main
git remote add origin https://github.com/<your-username>/emc-studio.git
git push -u origin main
```
Then: repository *Settings > Pages > Deploy from branch > main / root*.

## Notes
Estimates for learning and pre-compliance screening, not a substitute for accredited lab measurement.
Limit tables: ICNIRP 10 MHz to 300 GHz, CISPR 32 and FCC 15 from 30 MHz to 1 GHz.
