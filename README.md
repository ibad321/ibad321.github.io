# Ibad Ullah's Homepage

Academic homepage for Ibad Ullah, PhD student at the College of Intelligence and Computing, Tianjin University.

Live site: https://ibad321.github.io

Built with [Jekyll](https://jekyllrb.com/) and the [Academic Pages](https://github.com/academicpages/academicpages.github.io) theme (MIT licensed, see `LICENSE`).

## Updating the site

* Site settings and sidebar profile: `_config.yml`
* Top navigation: `_data/navigation.yml`
* Pages: `_pages/` (about, news, cv, awards, projects)
* Publications: one Markdown file per paper in `_publications/` (`category: published` or `category: under-review`)
* Talks: one Markdown file per talk in `_talks/`
* Static files such as the CV PDF: `files/` (served at `/files/...`)
* Profile photo: `images/profile.png` (400x400)

## Running locally

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

The site is then available at http://localhost:4000.
