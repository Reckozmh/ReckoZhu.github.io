# Recko Zhu — Academic Homepage

Personal academic website built with [AcademicPages](https://github.com/academicpages/academicpages.github.io) and Jekyll.

## Local preview

With Ruby and Bundler installed:

```bash
bundle install
bundle exec jekyll serve --baseurl ""
```

Then open `http://127.0.0.1:4000/`.

With Docker:

```bash
docker compose up
```

## GitHub Pages

The repository is configured as a project site:

- URL: `https://reckozmh.github.io/ReckoZhu.github.io/`
- Repository: `Reckozmh/ReckoZhu.github.io`
- Base path: `/ReckoZhu.github.io`

Before the first deployment, open **Settings → Pages → Build and deployment** and select **GitHub Actions** as the source. The workflow in `.github/workflows/pages.yml` builds and deploys pushes to `main`.

## Content maintenance

- Homepage: `_pages/about.md`
- Publication list: `_publications/*.md`
- Navigation: `_data/navigation.yml`
- Site and author metadata: `_config.yml`
- CV summary: `_pages/cv.md`
- Publication images: `images/publications/`
- PDFs: `files/papers/`

Search for `TODO` before publishing. These markers intentionally identify information or links that were not present or were inconsistent in the supplied materials.

## Credits

The theme is based on AcademicPages and Minimal Mistakes. See `LICENSE` for the inherited template license.
