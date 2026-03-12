---
title: "Hello World - Welcome to My Blog"
description: "My first blog post — introducing the new site built with Hugo and Stack theme."
date: 2026-03-12
slug: "hello-world"
categories:
  - General
tags:
  - Blog
  - Intro
---

## Welcome

Hello! This is my first post on the new blog, powered by [Hugo](https://gohugo.io/) and the [Stack](https://github.com/CaiJimmy/hugo-theme-stack) theme.

I migrated my old academic homepage (built with MkDocs) to this new setup, which offers:

- **Blog support** with tags, categories, and archives
- **Full-text search** across all content
- **Dark/Light mode** toggle
- **Comments** via [Giscus](https://giscus.app/)
- **RSS feed** for subscribers

## What I'll Write About

I plan to share content on:

1. **AI Infrastructure** — deep learning compilers, model optimization
2. **CUDA Programming** — kernel optimization, HGEMM, Tensor Core
3. **System Design** — engineering best practices, tooling
4. **Miscellaneous** — book reviews, personal reflections

## How This Site Works

The entire site is built with Hugo, a blazing-fast static site generator. Articles are written in Markdown and automatically deployed to GitHub Pages via GitHub Actions on every push.

```bash
# Create a new post
hugo new blog/my-new-post/index.md

# Preview locally
hugo server -D

# Push to deploy
git add . && git commit -m "new post" && git push
```

Stay tuned for more posts!
