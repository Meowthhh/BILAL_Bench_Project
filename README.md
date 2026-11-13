# BILAL-Bench project page

Static site for the paper "Do Open Language Models Invent Scripture? BILAL-Bench: Benchmarking Islamic-Source Fabrication in Bengali". No build step: plain HTML and CSS.

## Publish with GitHub Pages

1. Copy this `docs/` folder into the root of your repository (for example `Meowthhh/BILAL-Bench`).
2. Commit and push.
3. On GitHub: Settings → Pages → Source "Deploy from a branch" → Branch `main`, folder `/docs` → Save.
4. After a minute the site is live at `https://<username>.github.io/<repository>/`.

## Files

- `index.html`: the whole page (charts are HTML/CSS/SVG, no images needed)
- `assets/BILAL-Bench_paper.pdf`: the "Paper" button target
- `assets/poster.png`: the workshop poster
- `assets/social-card.png`: preview image for link sharing
- `assets/favicon.png`: tab icon
- `.nojekyll`: tells GitHub Pages to serve the files as they are

## Things you may want to edit

- **Paper link**: to point at OpenReview or arXiv instead of the bundled PDF, change the `href` of the "Paper" button in `index.html`.
- **Link previews**: social sites need an absolute image URL. Once the site is live, change `og:image` in the `<head>` of `index.html` to `https://<username>.github.io/<repository>/assets/social-card.png`.
- **BibTeX**: update the entry in the "Cite" section when the official proceedings entry is available.
