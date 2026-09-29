# Jonny Hughes

Source for my personal site: **<https://jrhughes003.github.io/Jonny-Hughes/>**

One static page, `index.html` plus `styles.css`, with no JavaScript and no build step. It's served by GitHub Pages from `main`, so a push republishes it.

## Editing

- Content lives in `index.html`, grouped into Work, Projects, Skills and Contact sections.
- Colours and fonts are set once as variables at the top of `styles.css`. Dark mode follows the visitor's system setting.
- After changing `styles.css`, bump the `?v=` number on its `<link>` in `index.html` so visitors' browsers fetch the new file instead of a cached copy.
- To preview locally, open `index.html` in a browser, or run `python -m http.server` in this folder.
