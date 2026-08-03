# Fengyuan Liu Academic Homepage

Personal academic homepage for Fengyuan Liu.

Website: https://uwfengyuan.github.io/fengyuan-academic-homepage/

This site is built with Jekyll and adapted from the public
[`academic-homepage`](https://github.com/luost26/academic-homepage) template.

## Content

- Profile, bio, education, and experience: `_data/profile.yml`
- Homepage section visibility: `_data/display.yml`
- Navigation items: `_data/navigation.yml`
- News entries: `_news/`
- Publications: `_publications/`
- Publication preview images: `assets/images/covers/`
- Portrait image: `assets/images/photos/fengyuan_liu.jpg`
- Site styling: `assets/css/global.css`

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
