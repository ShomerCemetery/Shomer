# SHOMER GitHub Pages upload guide

## What is in this package
- `index.html` — the website homepage
- `credits.html` — photo credits and source notes
- `images/hero/` — hero background image
- `images/gallery/` — selected locally hosted gallery images
- `.nojekyll` — disables Jekyll processing on GitHub Pages for a plain static site

## Recommended repository structure
```text
/index.html
/credits.html
/.nojekyll
/images/hero/karnobat-hero-202.jpg
/images/gallery/karnobat-005.jpg
/images/gallery/karnobat-006.jpg
...
```

## Upload on GitHub — browser method
1. Open your repository on GitHub.
2. If `index.html` already exists, open it and choose **Edit** or delete/replace it.
3. At the repository root, upload these files from this package:
   - `index.html`
   - `credits.html`
   - `.nojekyll`
4. Create a folder named `images`.
5. Inside `images`, create a folder named `hero` and upload `karnobat-hero-202.jpg`.
6. Inside `images`, create a folder named `gallery` and upload all `karnobat-*.jpg` gallery files.
7. Commit the changes.
8. In your repository, go to **Settings → Pages**.
9. Under **Build and deployment**, choose **Deploy from a branch**.
10. Set the branch to `main` (or your live branch) and the folder to `/ (root)`.
11. Save.
12. Wait a few minutes and open your GitHub Pages URL.

## Important notes
- Keep the file and folder names exactly the same. The HTML uses relative paths such as `./images/gallery/karnobat-005.jpg`.
- Because this is a project site, relative paths are safer than full GitHub `blob` URLs.
- If the site does not update right away, wait a few minutes and hard refresh the browser.
- Before adding more Wikimedia Commons files later, verify the license on each file page.
