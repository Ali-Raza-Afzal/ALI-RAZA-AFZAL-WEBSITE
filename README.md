# Ali Raza Afzal — Author Website

A static HTML/CSS website (no JavaScript, no frameworks) for author Ali Raza Afzal, featuring his novel **Dam-e-Waris (دَمِ وارث)**.

## Folder structure

```
index.html              → Homepage
dam-e-waris.html         → Dedicated novel page
css/
  style.css              → All styling (colors, type, layout)
images/
  author.jpg              → Author portrait (hero + about section)
  dam-e-waris-cover.jpg   → Novel cover (homepage + novel page)
  review-01.jpg … review-06.jpg → Reader review screenshots
pdf/
  dam-e-waris.pdf          → The novel PDF, embedded in the reader on dam-e-waris.html
```

## Replacing the placeholder assets

Every image and the PDF above are currently soft pastel **placeholder files** so the site
renders correctly right away. To finish the site, simply **overwrite each file with your
real asset using the exact same filename** — no HTML or CSS editing required:

| Replace this file | With |
|---|---|
| `images/author.jpg` | Your author portrait |
| `images/dam-e-waris-cover.jpg` | The Dam-e-Waris book cover |
| `images/review-01.jpg` … `review-06.jpg` | Screenshots of reader reviews (add/remove `<img>` tags in the "What Readers Say" section of `index.html` if you have more or fewer than 6) |
| `pdf/dam-e-waris.pdf` | The real novel PDF |

## Adding your Instagram and Pratilipi links

Search each HTML file for `REPLACE_WITH_` and swap in your real URLs. These appear in:
- The "Let's Connect" section and footer of `index.html`
- The "Prefer Reading on Pratilipi?" and "Follow the Journey" sections and footer of `dam-e-waris.html`

## Deploying to GitHub Pages

1. Create a new GitHub repository.
2. Upload this entire folder's contents (keeping the same structure) to the repository root.
3. In the repository, go to **Settings → Pages**, set the source branch (usually `main`) and folder (`/root`).
4. Save — your site will be live at `https://<your-username>.github.io/<repo-name>/`.

No build step, bundler, or server is required — this is a plain static site.
