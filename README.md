# karlchawalla-dev.github.io

Personal GitHub Pages site hosting self-contained HTML widgets for Staffbase demos.

- **Live base URL:** https://karlchawalla-dev.github.io/
- **Widgets folder:** [`bk/`](bk/) → served at `https://karlchawalla-dev.github.io/bk/<widget>.html`

Each widget is a single self-contained `.html` file (inline CSS + vanilla JS, no
build step, no dependencies), embedded into Staffbase via the Embedded Content
widget. Open any file directly in a browser to preview it.

## Publishing

1. Create the repo `karlchawalla-dev.github.io` on GitHub (public).
2. `git push` this repo to it.
3. Settings → Pages → Source: `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Widgets go live at `https://karlchawalla-dev.github.io/bk/<file>.html`.

The `.nojekyll` file at the root disables Jekyll so files are served verbatim.
