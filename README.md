# Fengyuan Liu Academic Homepage

Personal academic homepage for Fengyuan Liu.

Website: https://uwfengyuan.github.io/fengyuan-academic-homepage/

This site is built with Jekyll and adapted from the public
[`academic-homepage`](https://github.com/luost26/academic-homepage) template.

## Content

The site follows a simple Jekyll structure:

- profile data and homepage section configuration live under `_data/`
- news entries live under `_news/`
- publications live under `_publications/`
- reusable page components live under `_includes/`
- layouts live under `_layouts/`
- static assets and styling live under `assets/`

## Publications

Each publication is a Markdown file under `_publications/<year>/` with YAML front matter.

The homepage shows papers with `selected: true`.

Publication links follow this convention:

- `Paper`: direct PDF link
- `Code`: source code repository, when available
- `Prompt`: prompt repository, when available
- `Scholar`: Google Scholar entry

Do not add a separate `PDF` link; `Paper` already points to the PDF.

## Local Preview

Install Ruby/Jekyll dependencies, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open the local URL printed by Jekyll.

## Deployment

The site is deployed with GitHub Pages from:

```text
uwFengyuan/fengyuan-academic-homepage
```

After editing locally:

```bash
git add .
git commit -m "Update academic homepage"
git push
```

GitHub Pages will rebuild the public site after the push.
