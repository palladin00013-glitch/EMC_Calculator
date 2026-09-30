# EMF Buddies (Awareness folder)

Playful web app with original mascots (Zappy and Wavey). Plain HTML, CSS and JavaScript, no build step.

| File | Purpose |
|---|---|
| `index.html` | Page shell, header, bottom navigation |
| `style.css` | Light/dark theme tokens and playful layout |
| `app.js` | Home, Settings, Room Scanner, Distance Fun, Habit Tracker, Facts, mascots |

## Run in VS Code
1. File > Open Folder > `emf-buddies`
2. Install the **Live Server** extension
3. Right-click `index.html` > *Open with Live Server*

(No extension? Run `python -m http.server 8000` and open http://localhost:8000)

## Push to GitHub and host free
```bash
git init
git add .
git commit -m "EMF Buddies awareness app"
git branch -M main
git remote add origin https://github.com/<your-username>/emf-buddies.git
git push -u origin main
```
Then: repo Settings > Pages > Deploy from branch > main / root.

## Technical space (hidden)
Off by default. Turn on in the top-bar ⚙️ Settings > "Show the Technical space" to reveal a Technical button (placeholder for now).

## Next: build it
Add a `technical/` section (RF solver, shielding, units, limits). Formulas are already in the earlier `emc-studio/app.js` and `emc-calculator/emc_calc.py`.

## Notes
Estimates for education only. Room Scanner assumes every device transmits at full power at once (worst case) and compares against ICNIRP public reference levels. It is not a medical assessment.
