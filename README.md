# Gayness, Eigenforms, and Bodies

A serial exploration of the resonances between mathematical structures, embodied experience, and queer being.

## Setup Instructions

### 1. Create the GitHub Repository

Go to https://github.com/new and create a repository named exactly: `miriamsimone.github.io`

Make it public and don't initialize it with any files.

### 2. Push this code to GitHub

```bash
cd /path/to/this/folder
git init
git add .
git commit -m "Initial commit: Gayness, Eigenforms, and Bodies"
git branch -M main
git remote add origin https://github.com/miriamsimone/miriamsimone.github.io.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" → "Pages"
3. Under "Source", select "Deploy from a branch"
4. Select branch: `main` and folder: `/ (root)`
5. Click "Save"

Your site will be live at: https://miriamsimone.github.io in a few minutes!

## Writing New Posts

Create a new file in `_posts/` with the format: `YYYY-MM-DD-title-slug.md`

Example:
```yaml
---
layout: post
title: "Your Essay Title"
date: 2024-11-18
reading_time: 10
---

Your content here. You can use:

- Inline math: $E = mc^2$
- Display math: $$\int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2}$$
- Headers, links, all the usual markdown
```

## Local Testing (Optional)

If you want to preview locally before pushing:

```bash
bundle install
bundle exec jekyll serve
```

Then visit http://localhost:4000

## Customization

Edit `_config.yml` to update:
- Your email
- Social media links
- Site description

## RSS Feed

Your RSS feed will automatically be available at: https://miriamsimone.github.io/feed.xml

People can subscribe using any RSS reader!
