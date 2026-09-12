# Ismail Kotbi Portfolio

Static editorial portfolio site for Ismail Kotbi, built with semantic HTML, CSS, and vanilla JavaScript so it can deploy to any static host without a build step.

## Run locally

From this folder:

```bash
python3 -m http.server 4173
```

Open `http://localhost:4173`.

## Replacing photography

Portfolio items live in the `projects` array in `script.js`. The current local files are `hero.png` and `1.jpeg` through `5.jpeg`. Replace those filenames with paths such as `/public/images/editorial/quiet-forms.jpg` when organizing the final production assets. Hero, campaign, and social images are referenced in `index.html` and can be swapped in the same way.
