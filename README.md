# ZQPei.github.io

Personal blog and profile site built with [Hugo](https://gohugo.io/) and [Stack](https://github.com/CaiJimmy/hugo-theme-stack) theme.

**Live site**: [zqpei.github.io](https://zqpei.github.io)

## Quick Start

```bash
# Install Hugo (macOS)
brew install hugo

# Clone with submodules
git clone --recursive https://github.com/ZQPei/ZQPei.github.io.git
cd ZQPei.github.io

# Local preview
hugo server -D --bind 0.0.0.0 --port 1313
# Open http://localhost:1313/
```

## Write a New Post

```bash
# Create post directory
mkdir -p content/blog/my-new-post

# Create content file: content/blog/my-new-post/index.md
```

Post front matter template:

```yaml
---
title: "Post Title"
date: 2026-03-12
slug: "post-title"
description: "A brief description"
categories:
  - Category
tags:
  - Tag1
  - Tag2
---
```

## Project Structure

```
├── config/_default/        # Site configuration
│   ├── hugo.toml           # Main config
│   ├── params.toml         # Theme params & Giscus comments
│   ├── menu.toml           # Social links
│   ├── markup.toml         # Markdown rendering
│   └── related.toml        # Related posts
├── content/
│   ├── blog/               # Blog posts → /blog
│   └── page/               # Static pages
│       ├── profile/        # → /profile
│       ├── archives/       # → /archives
│       └── search/         # → /search
├── assets/icons/           # Custom SVG icons
├── static/
│   └── images/             # Static images
├── themes/hugo-theme-stack/ # Stack theme (git submodule)
└── .github/workflows/      # GitHub Actions auto-deploy
```

## Deployment

Pushing to `master` triggers GitHub Actions to build and deploy automatically.

## License

Content: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
Code: [MIT](https://opensource.org/licenses/MIT)
