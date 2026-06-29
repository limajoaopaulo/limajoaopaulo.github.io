# limajoaopaulo.github.io

Personal academic website of **João Paulo D. Lima**, PhD Candidate in Economics at Université Paris Dauphine – PSL (LEDa-DIAL / IRD-DIAL), PRESILIENT project (Horizon Europe / MSCA).

Live at <https://limajoaopaulo.github.io>.

## Stack

- [Jekyll 4](https://jekyllrb.com/) static site, built on the [Gradfolio](https://github.com/jitinnair1/gradfolio) theme (vendored into the repo).
- Bilingual: English homepage (`index.md`) and Portuguese version (`_pages/pt/index.md`).
- Content pages live in `_pages/` (`research.md`, `projects.md`, `cv.md`).
- Styles in `assets/css/` (SCSS compiled by Jekyll). Navigation in `_includes/navigation.html`.
- Deployed automatically to GitHub Pages via `.github/workflows/pages.yml` on push to `master`.

## Local development

```sh
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Editing content

- **Bio:** `index.md` (English) and `_pages/pt/index.md` (Portuguese).
- **Research:** `_pages/research.md` (working papers, work in progress, publications, conferences).
- **Projects:** `_pages/projects.md`.
- **CV:** `_pages/cv.md` and the PDF in `assets/docs/`.
- **Profile photo:** `assets/images/profile.png`.
- **Social links / site title:** `_config.yml`.

## Credits

Built on the [Gradfolio](https://github.com/jitinnair1/gradfolio) theme by Jitin Nair (MIT, see `LICENSE`). Content © João Paulo D. Lima.
