# Maria Nocchi — personal academic homepage

A lightweight static academic homepage. No framework, build step, or external font is required.

## Files

- `index.html` — the website.
- `photo.jpg` — add this later when the portrait is chosen.
- `cv.pdf` — optional; add this later if you want a direct CV link.

## Add the portrait

1. Save the chosen portrait as `photo.jpg` in the same folder as `index.html`.
2. In `index.html`, find the `portrait` block.
3. Replace the placeholder note with:

```html
<img src="photo.jpg" alt="Portrait of Maria Nocchi">
```

## Add a CV link later

Put `cv.pdf` in the same folder and add this wherever you want the link:

```html
<a href="cv.pdf" target="_blank">CV</a>
```

## Publish with GitHub Pages

For a personal homepage at `https://YOURUSERNAME.github.io/`, create a public repository named exactly:

`YOURUSERNAME.github.io`

Then upload `index.html` (and later `photo.jpg` / `cv.pdf`) to the root of the repository.

In the repository go to:

**Settings → Pages → Build and deployment → Source: Deploy from a branch**

Choose:

- Branch: `main`
- Folder: `/(root)`

Save. GitHub will publish the page. The public URL stays the same when you update the files later.
