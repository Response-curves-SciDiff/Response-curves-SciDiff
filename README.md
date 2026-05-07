# SciDiff-RC Project Page

Static, anonymized project page for *Response Curves Reveal Accuracy-Limited
Step-Size Laws in Scientific Diffusion Samplers* (project alias **SciDiff-RC**).

## Files

- `index.html` --- the page itself; pulls Bulma, FontAwesome, and Academicons
  from public CDNs.
- `static/css/style.css` --- minimal custom styles on top of Bulma.
- `static/images/` --- four headline figures (overview, multi-threshold
  validation, held-out pass rates, schedule audit scatter).
- `.nojekyll` --- forces GitHub Pages to serve files as-is (no Jekyll build).

## Local preview

```bash
cd webpage
python -m http.server 8000
# visit http://localhost:8000
```

## Deploy on GitHub Pages

1. Push the contents of `webpage/` to the root (or `docs/`) of an anonymous
   GitHub repository. Do **not** put the page in a repo whose name or owner
   leaks the authors during the review period.
2. In *Settings &rarr; Pages*, set the source to the appropriate branch and
   directory. The page will be served at
   `https://<owner>.github.io/<repo>/`.

## Anonymity

- Authors are listed as "Anonymous Author(s)" with no affiliation.
- Paper / Supplementary / Code links are placeholders (`href="#"`); fill
  them in once an anonymous host is decided.
- The footer credits the page-template lineage, not the authors.
