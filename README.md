# WB Students Group — GitHub Pages (Free)

This repo uses a static `index.html` and `data.json` to show Latest, Books, Routines, Contributors and an Image Slider.
Admin edits content via the site's Admin Panel (local preview) and publishes changes by pasting generated JSON into `data.json` and committing.

## Quick setup
1. Create a public repo on GitHub (e.g., `wb-students-site`).
2. Paste `index.html`, `data.json`, `README.md` to repo root.
3. Upload assets:
   - Create folders `assets/pdfs/`, `assets/images/`, `assets/slides/`
   - Upload PDFs/images via GitHub UI
   - Copy raw URLs (click file → Raw)
4. Replace `YOUR_GITHUB_USERNAME` and `YOUR_REPO` in `data.json`.
5. Enable GitHub Pages (Settings → Pages → Branch: main → Folder: root).
6. Visit site URL: `https://<username>.github.io/<repo>/`

## Admin flow
- Click **Admin** on site → enter password (`iyradmin` by default).
- Use forms to add Book, Routine, Update, Slide image, Contributor, Counters.
- Click **Copy JSON** → open GitHub `data.json` edit → paste → commit.
- Upload any referenced images/PDFs to `assets/...` before using their raw URLs.

## Notes
- Admin password is client-side convenience only. Actual protection comes from GitHub repo permissions.
- Do not store secrets in `index.html` or `data.json`.

