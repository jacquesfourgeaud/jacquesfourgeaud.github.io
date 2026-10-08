# Personal website of Jacques Fourgeaud

Static HTML site (no build step) ready for GitHub Pages.

## Deploy in 5 minutes
1. Create a GitHub account (if needed) and a new public repository named exactly `<your-username>.github.io`.
2. Upload every file and folder of this directory (index.html, research.html, publications.html, contact.html, Fourgeaud_CV.pdf, assets/) to the root of the repository.
3. In the repository, go to Settings > Pages and check that "Deploy from a branch" / branch `main` / folder `/ (root)` is selected.
4. After one or two minutes the site is live at `https://<your-username>.github.io/`.

## Customize
- Photo: add a square picture named `assets/profile.jpg` (about 400x400 px). It is picked up automatically.
- CV: replace `Fourgeaud_CV.pdf` with a newer version whenever needed (same file name).
- Text: edit the HTML files directly, or edit `build_site.py` and run `python3 build_site.py` to regenerate the four pages consistently.
- Style: `assets/style.css`.
