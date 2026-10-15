# Sudha M Portfolio

Static site: HTML, CSS, vanilla JS. No build step.

## Preview locally
Open `index.html` in a browser, or run `python3 -m http.server 8000` in this folder and visit http://localhost:8000.

## Before publishing
Resume details are filled in. Edit text directly in `index.html`.

## GitHub
1. Create a new empty repo on github.com (e.g. `portfolio`).
2. In this folder: `git init && git add . && git commit -m "Initial portfolio" && git branch -M main`
3. `git remote add origin https://github.com/sudha-Ms/portfolio.git && git push -u origin main`

## Netlify (free)
1. Sign in at netlify.com with GitHub, then Add new site > Import an existing project.
2. Pick the repo. Build command: leave empty. Publish directory: `.` (already set in netlify.toml).
3. Deploy. Optionally rename the site under Site configuration > Change site name.

## Updating later
Edit files, then `git add . && git commit -m "Update" && git push`. Netlify redeploys automatically.
