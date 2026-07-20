# Hawaii Salsa & Bachata Paradise 2026 - Road to Waikiki

A one-page showcase for the trip (Sept 3-6, 2026, Waikiki): the booked plan, the festival schedule, a 6-week dance training brief for the interim, and the cost breakdown. Live countdown to departure.

Single self-contained `index.html`. No build step. Google Fonts loaded via CDN (fine on GitHub Pages).

## Deploy to GitHub Pages

Personal account is `elijahcarimbocas` (same as the Dance Star site). Two options:

### Option A - new repo (recommended)
```bash
cd "path/to/site"
git init
git add index.html README.md
git commit -m "Hawaii Salsa Bachata Paradise 2026 site"
gh repo create hawaii-bachata-2026 --public --source=. --push
```
Then in the repo: Settings > Pages > Source = `main` branch, `/root`. Live at:
`https://elijahcarimbocas.github.io/hawaii-bachata-2026/`

### Option B - drop into the existing dance-star repo
Copy `index.html` into a `hawaii/` folder of that repo and push. Live at:
`https://elijahcarimbocas.github.io/dance-star/hawaii/`

## Edit
Everything is in `index.html` - content, styles, and the countdown script are inline. Update the training weeks, dates, or numbers directly in the markup.
