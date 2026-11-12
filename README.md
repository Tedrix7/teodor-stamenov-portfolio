# Teodor Stamenov – portfolio website

A static site: `index.html` plus the `img/` folder. No build step.

## Run locally
Open a terminal in this folder and run `python3 -m http.server`, then visit http://localhost:8000
(opening index.html directly also works, but the hero particle cloud needs a local server).

## Host it for free
- **Netlify**: drag this folder onto https://app.netlify.com/drop
- **GitHub Pages**: push `index.html` and `img/` to a repo, then Settings → Pages → deploy from the main branch.

## Editing content
All project text and images live in the `WORK` and `PROJECTS` arrays near the top of the `<script>` in index.html.
Images are in `img/` (WebP, extracted from the PDF).
