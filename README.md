# edinburghcora.github.io

The site is built by GitHub Pages (Jekyll) and published at https://edinburghcora.github.io/.

- `index.md` — the page. Edit the text here; Markdown works inside the `markdown="1"` blocks.
- `_layouts/default.html` — the page frame (fonts, width). Rarely needs changing.
- `assets/images/` — images stored in the repo. `step-2.jpg` is the worked example; reference a file here as
  `<img src="{{ '/assets/images/your-file.jpg' | relative_url }}" alt="...">`.
  Step 1 and the logo show the other option: an `https://` URL to an image hosted elsewhere.
- `_config.yml` — the site title.

Pushing to `main` republishes the site within a minute or two (see the Actions tab).
