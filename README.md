# Arijeet Singh — Portfolio

Single-file static site (`index.html`): no build step, no dependencies.

## Deploy on GitHub Pages

1. Create a new public repo named `notarijeet.github.io` (this gives you the root URL `https://notarijeet.github.io`). Any other repo name also works and is served at `https://notarijeet.github.io/<repo-name>/`.
2. From this folder:
   ```bash
   git init
   git add .
   git commit -m "Add portfolio"
   git branch -M main
   git remote add origin https://github.com/notarijeet/notarijeet.github.io.git
   git push -u origin main
   ```
3. In the repo go to **Settings → Pages**, set **Source** to **Deploy from a branch**, choose **main** and **/ (root)**, then save.
4. After a minute or two the site is live.

## Edit

All content is plain HTML inside `index.html`. Add projects by copying a `<div class="item">` block in the projects section.
