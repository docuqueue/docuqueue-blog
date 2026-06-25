# DocuQueue Blog

Professional PDF generation — templates, APIs, and the art of looking legitimate.

## Writing a post

1. Create a new file in `_posts/` with the format `YYYY-MM-DD-title-slug.md`
2. Add front matter at the top:

```yaml
---
layout: single
title: "Your Post Title"
date: 2026-06-26
classes: wide
categories: ["Productivity"]
tags: ["tag1", "tag2"]
excerpt: "One sentence summary."
---
```

3. Write your post in markdown below the front matter
4. Push to `main` — GitHub Pages builds and deploys automatically

## Local development

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`

## Deploying

Push to `main`. GitHub Pages builds and deploys on every push.

## Adding pages

Create a markdown file with front matter:

```yaml
---
layout: single
title: "Page Title"
permalink: /your-page/
---
```
