# Farshid Farshidfar - personal website

A static GitHub Pages site, with no build step, JavaScript dependency or external
font service. The page presents research and mathematical background for academic
and non-academic readers.

## Updating the site

- Edit `index.html` to update text and `styles.css` to update the layout.
- Replace `assets/farshid-farshidfar-cv.pdf` with the latest compiled public CV.
- Update the dates in the CV panel, footer and `sitemap.xml` together.
- Keep manuscript status accurate; add preprint links only when publicly available.
- Manuscripts are in final preparation; the December 2026 arXiv forecast is the
  author's estimate as of October 2026 and should be revised when needed.
- Describe machine learning as an interest unless further experience is added.

The CV source and its independent local Git history are not part of this
repository. Only the public PDF belongs here.

To preview locally, run `python -m http.server 8765 --bind 127.0.0.1` in this
folder, then open `http://127.0.0.1:8765`. GitHub Pages serves the default branch.
