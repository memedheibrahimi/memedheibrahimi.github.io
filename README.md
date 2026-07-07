# memedheibrahimi.github.io

Personal academic website of **Memedhe Ibrahimi** — Assistant Professor (RTDa) at Politecnico di Milano (DEIB, BONSAI Lab).

Built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme. Sections: about, news, publications, teaching.

## Editing

- **About / bio:** `_pages/about.md`
- **News:** add a Markdown file in `_news/` (copy an existing one; the `date:` field controls ordering)
- **Publications:** edit `_bibliography/papers.bib` (set `selected={true}` to feature a paper on the homepage)
- **Teaching:** edit the course files in `_teachings/`
- **Profile photo:** replace `assets/img/prof_pic.jpg`
- **Links / email:** `_data/socials.yml`
- **Global settings:** `_config.yml`

## Deploy (GitHub Pages)

1. Push this repository to `https://github.com/memedheibrahimi/memedheibrahimi.github.io` on the `main` branch.
2. The included GitHub Action (`.github/workflows/deploy.yml`) builds the site and publishes it to the `gh-pages` branch.
3. In **Settings → Pages**, set **Source = Deploy from a branch**, **Branch = `gh-pages` / (root)**.
4. The site goes live at `https://memedheibrahimi.github.io`.
