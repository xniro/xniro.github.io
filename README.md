# terminal-theme

A minimal amber-on-black terminal Jekyll theme for GitHub Pages.

## Quick start

```bash
gem install bundler jekyll
bundle install
bundle exec jekyll serve
# → http://localhost:4000
```

## Deploying to GitHub Pages

1. Push this repo to `github.com/yourusername/yourusername.github.io`
2. In Settings → Pages → set source to `main` branch, `/ (root)`
3. Done — GitHub builds and deploys automatically

Or use the `gh-pages` branch approach if it's a project site.

## Customising

**`_config.yml`** — update `title`, `author`, `github_username`, `email`, etc.

**`index.html`** — edit the About text, swap out projects, add contact links.

**`_posts/`** — add `YYYY-MM-DD-title.md` files with front matter:
```yaml
---
layout: post
title: "Your post title"
date: 2025-01-01
tags: [tag1, tag2]
---
```

**`assets/css/main.scss`** — CSS variables at the top control the whole palette.
Change `--amber` / `--bg` / `--font-mono` to retheme instantly.

## File structure

```
terminal-theme/
├── _config.yml          # site settings
├── _layouts/
│   ├── default.html     # sidebar + main wrapper
│   └── post.html        # blog post layout
├── _posts/              # your blog posts (markdown)
├── assets/
│   └── css/
│       └── main.scss    # all styles
├── index.html           # homepage (about/projects/blog/contact)
└── Gemfile
```
