# My Web Wiki (GitHub Pages)

This repository now contains a simple placeholder website published from the `gh-pages` branch.

What I did
- Created a `gh-pages` branch and added an `index.html` placeholder for GitHub Pages.

Where it will be published
- URL: https://paurushtaunk.github.io/my-web-wiki/ (may take a minute to appear)

How to update the site
- Edit `index.html` directly in the `gh-pages` branch, or clone the repo and push changes to that branch.

Quick Git commands (local)

```bash
# clone
git clone https://github.com/paurushtaunk/my-web-wiki.git
cd my-web-wiki
# switch to the gh-pages branch
git checkout gh-pages
# edit files, then:
git add .
git commit -m "Update site"
git push origin gh-pages
```

If GitHub Pages does not show the site automatically:
1. Go to the repository Settings → Pages.
2. Under "Source", select the `gh-pages` branch (root) and Save.
3. GitHub will show the published URL after a moment.

Notes
- If you prefer Pages from `/docs` on the default branch, I can move the files there instead.
- Want extra pages (about/contact/portfolio)? Tell me and I'll add them.
