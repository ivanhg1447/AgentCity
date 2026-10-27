# Blog

Personal blog: Quarto website, hosted on GitHub Pages, mirrored free on Substack. No paywall; donations only, if ever.

## Local preview

```bash
quarto preview
```

## Publish

Push to `main` and the GitHub Action in `.github/workflows/publish.yml`
renders and publishes to the `gh-pages` branch. In the repository settings,
set Pages to deploy from the `gh-pages` branch.

## Adding a post

Add a `.qmd` file under `posts/` with title, date, and categories in the
front matter. It appears on the home page automatically.

## Notes

- Canonical home is this site on its own domain (to be connected).
- Substack mirrors are published a few days after the site, with a link back
  to the original post here.
- Quarto is installed on the Muse VM at `~/.local/quarto/bin/quarto`.
