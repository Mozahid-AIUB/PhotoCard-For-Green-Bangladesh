# সাতক্ষীরা বোটানিক্যাল সোসাইটি — Photocard Maker

A single-page web app. Anyone opens the link, uploads their photo, types their name &
designation, and downloads a premium 1080×1350 photocard. No backend, no cost.

## 1. Add the logo (important)
Save the green circular **SATKHIRA BOTANICAL SOCIETY** seal as a file named **`logo.png`**
in this folder (next to `index.html`).
- If `logo.png` is missing, a clean leaf-seal fallback is drawn automatically — so it still works.

## 2. Try it locally
Just double-click `index.html` to open it in your browser. Done.

## 3. Publish (pick one — both free)

### Netlify (drag & drop, easiest)
1. Go to https://app.netlify.com/drop
2. Drag this whole **Photocard** folder onto the page.
3. You get a live link instantly. Share it.

### Render (static site)
1. Push this folder to a GitHub repo.
2. Render → New → **Static Site** → connect the repo.
3. Publish directory: `.` (root). Deploy. Share the link.

## What users can change
- **Photo** (upload + zoom + position)
- **Name** (Bangla)
- **Name** (English)
- **Designation**

Everything else (title, tagline, quote, colors, logo) is fixed brand identity.
The **month/year** auto-updates to the current month.

## Tech
- Plain HTML/CSS/JS, no build step.
- Fonts: Hind Siliguri, Baloo Da 2, Manrope (Google Fonts).
- PNG export: `html-to-image` (CDN). Needs internet on first load for fonts + that library.
# PhotoCard-For-Green-Bangladesh
