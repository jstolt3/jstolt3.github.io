# jstolt3.github.io

Personal site, built by GitHub Pages with Jekyll.

## Adding things

- **Article:** add `_posts/YYYY-MM-DD-short-title.md` with a `title:` in the front matter. It shows up on the home page and `/articles/`.
- **Interests:** edit `_data/interests.yml`.
- **New section** (projects, resume, ...): create `section-name/index.html` (or `.md`) with `layout: default`, then add it to `_data/navigation.yml`.
- **Links and contact info:** `_config.yml`.

## Preview locally

```
bundle install
bundle exec jekyll serve
```
