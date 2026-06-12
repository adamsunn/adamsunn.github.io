# adamsunn.github.io

Personal academic website for **Adam Sun**, served via GitHub Pages.

This is a static, single-page site (no build step). Design and CSS are adapted from
[Jon Barron's website](https://jonbarron.github.io/).

## Structure

```
index.html        # the whole page
stylesheet.css    # styles (Lato font, link colors, paper thumbnails)
images/           # profile photo + publication thumbnails
.nojekyll         # tells GitHub Pages to serve files as-is (no Jekyll build)
```

## Editing

- **Bio / links / publications:** edit `index.html` directly.
- **Add a paper:** copy a `<tr>...</tr>` block in the publications table, swap the
  thumbnail (`images/<name>_thumb.jpg`), title, author list, venue, and links.
  Add `bgcolor="#ffffd0"` to the `<tr>` to highlight it.
- **Profile photo:** replace `images/AdamSun.jpg` with a square headshot.

## Deploy

GitHub Pages → Settings → Pages → Build and deployment →
**Deploy from a branch → `main` → `/ (root)`**. No CI/build required.
