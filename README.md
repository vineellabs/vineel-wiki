# V/WIKI — Personal Knowledge Base

A minimal, fast personal knowledge base built with [Astro](https://astro.build). Deploy to Vercel in minutes.

## Setup

```bash
npm install
npm run dev       # http://localhost:4321
npm run build     # production build
```

## Adding Articles

Drop a `.md` file into `src/content/articles/` with this frontmatter:

```markdown
---
layout: "../../layouts/Article.astro"
title: "Your Article Title"
description: "One-line description shown on the card"
date: "2026-04-24"
tags: ["tag1", "tag2"]
source: "Source Name"          # optional
sourceUrl: "https://..."       # optional
---

Your markdown content here...
```

That's it. The homepage picks it up automatically.

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → New Project → Import your repo
3. Framework preset: **Astro** (auto-detected)
4. Click Deploy

Every `git push` auto-deploys. ✓
