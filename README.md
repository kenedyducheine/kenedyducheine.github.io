# kenedyducheine.github.io

My personal site, laid out like a magazine spread.

- **`index.html`**: the front page. A masthead, a nav band, then three columns:
  projects on the left (Grid Notes first), azine's A in the middle, and the
  "Hi, I'm Kenedy" letter on the right. Each project is one
  `<article class="card">` block; copy one to add another.
- **`azine.html`**: opens from the A. The summary, the stack, and the two
  system documents.
- **`style.css`**: the look of both pages. Colors, fonts and sizes are the
  settings at the top (`:root`), with a comment on each.
- **Documents:** `assets/azine-summary.pdf` and `assets/azine-architecture.pdf`
  (copies of `docs/` in the azine repo), with `assets/azine-*.jpg` pictures of
  their first pages. To refresh: copy the new PDFs in and rerun
  `pdftoppm -r 110 -f 1 -l 1 -jpeg -singlefile assets/azine-summary.pdf assets/azine-summary`
  (and the same for `azine-architecture`).
- **Art:** `assets/art/`, public domain works from The Metropolitan Museum of Art's
  Open Access collection.

GitHub Pages publishes the `main` branch automatically at https://kenedyducheine.github.io.
