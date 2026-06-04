# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Commands

```bash
# Install dependencies
bundle install

# Run local dev server (with live reload)
bundle exec jekyll serve

# Build the site
bundle exec jekyll build
```

## Architecture

This is a personal academic website built on the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme.

**Content files to edit:**
- `_pages/about.md` — Homepage bio and experience
- `_pages/publications.md` — Manually maintained publication list
- `cv.html` — CV page (embeds `assets/cv.pdf` via iframe)
- `_config.yml` — Site metadata, scholar settings, nav links

**Publications:** The site uses `jekyll-scholar` with `_bibliography/papers.bib` for BibTeX-based rendering (used separately from the manual list in `_pages/publications.md`). The scholar style is `biophysical-journal`, sorted descending by year.

**Layouts/includes:** `_layouts/` and `_includes/` contain the HTML templates. The `about` layout is the homepage layout. KaTeX is enabled for math rendering.

**Styles:** SCSS lives in `_sass/`. Theme color is controlled by `$theme-color` in `_sass/_variables.scss`.

**Deployment:** The `bin/deploy` script builds the site and force-pushes the `_site/` contents to the `gh-pages` branch. The site is hosted on GitHub Pages.
