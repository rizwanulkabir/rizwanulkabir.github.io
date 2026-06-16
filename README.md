# Personal Website — MD Rizwanul Kabir

A clean, responsive academic homepage built from my CV. Plain HTML/CSS/JS — no build step.

## Files
- `index.html` — all content (about, research, education, publications, projects, awards, skills, contact)
- `style.css` — styling (VT-inspired maroon theme)
- `script.js` — mobile nav + footer year
- `assets/profile.jpg` — profile photo (see below)

## Adding your photo
Drop a square photo named **`profile.jpg`** into the `assets/` folder.
If the file is missing, the site automatically shows your "RK" initials instead.
A square image (e.g. 600×600) works best.

## Preview locally
```
python -m http.server 5050
```
Then open http://localhost:5050

## Hosting
Deployed via GitHub Pages at `https://<username>.github.io`.
Any push to the `main` branch updates the live site automatically.
