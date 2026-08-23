# aditya-sripada.com

Personal site for Aditya Sripada — robotics engineer.

Built with [Jekyll](https://jekyllrb.com/) on a fork of the
[al-folio](https://github.com/alshedivat/al-folio) theme.
Deployed to GitHub Pages via `.github/workflows/deploy.yml`; the custom
domain is set in `CNAME`.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Layout

| Path              | Contents                                    |
| ----------------- | ------------------------------------------- |
| `_pages/`         | Top-level pages (about, projects, cv, …)    |
| `_projects/`      | Project entries                             |
| `_news/`          | News / announcement items                   |
| `_bibliography/`  | `papers.bib` — publications                 |
| `_data/cv.yml`    | Structured CV (experience, awards, service) |
| `assets/`         | Images, PDFs, styles                        |

## Important

`url` and `baseurl` in `_config.yml` must stay as `https://www.aditya-sripada.com`
and `""`. Reintroducing the theme's `/al-folio` baseurl breaks every internal
link and stylesheet on the site.
