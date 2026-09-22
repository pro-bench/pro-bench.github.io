# Pro-Bench project page

Static site: `index.html` + `assets/`. No build step.

## Before going public
1. Open `index.html` and fill in the `LINKS` object near the top of the script
   (paper, pdf, code, dataset, video). Empty links show "coming soon".
2. Check the BibTeX entry (venue, year, key) in the `#cite` section.
3. Check the categorical label in the hero (`HERO.cat`, currently "a door")
   against the dataset's mapping for that target.
4. Optional: add `assets/demo.mp4` and set `LINKS.video = "assets/demo.mp4"`.
5. Update `og:image` to an absolute URL once the site has a domain, so link
   previews show the image.

## Deploy on GitHub Pages
Push this folder to a repository (or a `docs/` folder / `gh-pages` branch) and
enable Pages in the repository settings. `.nojekyll` is included.
