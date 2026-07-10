# Personal Website — Starter Frame

A dark, "technical dossier" themed personal site: fine blueprint grid, amber
telemetry accents, and corner-bracket (calibration reticle) photo frames —
built to fit an engineering / aerospace portfolio. Plain HTML/CSS/JS, no
build step, ready for GitHub Pages.

## File structure

```
index.html              → main page (About, Experience, Projects, Skills, Contact)
css/style.css            → all styles + design tokens (colors, fonts, spacing)
js/main.js                → smooth-scroll active nav, mobile menu, slideshow
experience/exp-1.html     → "Learn More" detail page for experience #1
experience/exp-2.html     → detail page for experience #2
experience/exp-3.html     → detail page for experience #3
projects/proj-1.html      → "Learn More" detail page for project #1
projects/proj-2.html      → detail page for project #2
projects/proj-3.html      → detail page for project #3
images/                   → put your real photos here once you have them
```

## Publishing with GitHub Pages

1. Create a new GitHub repo (public), e.g. `your-username.github.io` for a
   root-level site, or any repo name for a project site.
2. Push these files to the repo root (keep the folder structure as-is).
3. In the repo: **Settings → Pages → Source** → select the `main` branch,
   folder `/ (root)` → Save.
4. Your site will be live at `https://your-username.github.io/` (or
   `https://your-username.github.io/repo-name/` for a project site) within
   a minute or two.

## What to fill in

Everything marked as a placeholder is easy to find:

- **Name/title** — top of `index.html` (`hero-name`, `hero-title`) and the
  `<title>` tags in every page.
- **About Me photos** — swap the 4 `placehold.co` image URLs inside
  `.slideshow-track` in `index.html` for your own images (drop files in
  `images/` and point the `src` there).
- **About Me bio** — replace the `.bio-block` placeholder lines/note with
  your intro paragraph.
- **Experience / Projects cards** — each `.entry-card` has a photo, company
  or project name, timeframe badge, role, and short description.
- **Detail pages** — each `exp-*.html` / `proj-*.html` has an Overview and a
  Gallery grid (3 placeholder photos + captions each — add more `.gallery-item`
  blocks if you want more photos).
- **Skills** — each `.skill-chip` in the Skills section is one skill; add or
  remove `<span class="skill-chip">...</span>` freely within each category.
- **Contact** — update the `mailto:` link and LinkedIn URL near the bottom
  of `index.html`.

## Notes

- All "photos" right now are placeholder graphics from placehold.co so
  nothing is broken before you add real images — just replace the `src`
  attributes.
- The nav automatically highlights the section you're scrolled to.
- Corner-bracket frames, section numbering, and the mono "spec tag" labels
  are the site's signature visual motif — reuse the `.bracket-frame` class
  anywhere you want that same framed look.
