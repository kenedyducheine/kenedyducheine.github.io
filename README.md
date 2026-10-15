# kenedyducheine.github.io

My personal site.

- **`index.html`**: the front page. A top bar (name, intro, links), then the page
  split in two: **Math** on the left and **Computer science** on the right, each
  side scrolling on its own. On phones the two sides become tabs. Each project is
  one `<article class="project">` block; copy one into either side to add a project
  (and update the count next to that side's heading).
- **`home.css`**: the look of the front page. Colors, fonts and sizes are the
  settings at the top (`:root`).
- **`azine.html`**: the azine write-up, linked from the azine project. It still
  uses **`style.css`**, the older magazine-style stylesheet.
- **Documents:** `assets/azine-summary.pdf` and `assets/azine-architecture.pdf`
  (copies of `docs/` in the azine repo), with `assets/azine-*.jpg` pictures of
  their first pages. To refresh: copy the new PDFs in and rerun
  `pdftoppm -r 110 -f 1 -l 1 -jpeg -singlefile assets/azine-summary.pdf assets/azine-summary`
  (and the same for `azine-architecture`).
- **Art:** `assets/art/`, public domain works from The Metropolitan Museum of Art's
  Open Access collection (no longer shown on the front page).

GitHub Pages publishes the `main` branch automatically at https://kenedyducheine.github.io.
