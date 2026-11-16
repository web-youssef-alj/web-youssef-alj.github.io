# Personal academic website

Static site (HTML + CSS, no build step), served by GitHub Pages.

- `index.html` — all content (about, news, publications, projects, teaching, contact)
- `style.css` — styles (light/dark mode automatic)
- `assets/img/` — profile photo (replace `profile.svg` or point the `<img>` to e.g. `profile.jpg`)
- `assets/papers/` — PDFs of papers
- `assets/cv.pdf` — your CV (linked from the top bar)

Preview locally: `python3 -m http.server` then open http://localhost:8000

## Template

The live pages are intentionally empty (headings only). A fully filled-in example
of every block is kept on the `template` branch:

    git show template:index.html
    git show template:teaching/ai-governance.html
