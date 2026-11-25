# my-site

My personal portfolio site. It's plain HTML and CSS with no build step, hosted on GitHub Pages.

**Live:** https://adhyamaddukuri-oss.github.io/my-site/

## Editing

- `index.html`: all the content. Look for `TODO` comments.
- `styles.css`: colors, fonts, and layout. The palette is defined in the `:root` variables at the top.
- `favicon.svg`: the browser tab icon.

To preview it locally, open `index.html` in a browser, or run:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying

Every push to `main` deploys automatically through GitHub Pages
(Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)`).
