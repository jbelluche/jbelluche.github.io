# Jack Belluche

Personal website and blog for [jbelluche.github.io](https://jbelluche.github.io), built with Astro and hosted on GitHub Pages.

## Write a post

Create a Markdown file in `src/content/blog/`. The filename becomes the URL slug.

```md
---
title: "An interesting title"
description: "A short summary shown on article lists and in search results."
pubDate: 2026-08-13
draft: true
---

Start writing here.
```

Set `draft: false` when the article is ready to publish.

Commit and push to `master`; GitHub Actions will build and publish the site automatically.

## Local development

```sh
npm install
npm run dev
```

Run `npm run build` before pushing substantial changes.
