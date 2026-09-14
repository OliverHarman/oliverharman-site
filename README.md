# oliverharman.me

Source for [oliverharman.me](https://www.oliverharman.me), built with
[Quarto](https://quarto.org).

## Editing

Open any `.qmd` file in VS Code and press **Ctrl+Shift+K** to preview. Saving
reloads the preview. From a terminal:

```bash
quarto preview     # live preview in the browser
quarto render      # build into _site/
```

## Publishing

```bash
quarto publish gh-pages
```

This builds the site and pushes it to the `gh-pages` branch, which GitHub Pages
serves.
