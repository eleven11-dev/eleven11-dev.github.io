# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a Jekyll-based GitHub Pages site (`eleven11-dev.github.io`) using the `minima` theme (v2.5) and Jekyll 4.4.x. Deployment is automatic via GitHub Actions on push to `main`.

## Development Commands

```bash
# Install dependencies
bundle install

# Serve locally with live reload
bundle exec jekyll serve

# Build site (output to _site/)
bundle exec jekyll build
```

Note: `_config.yml` changes require restarting the server — they are not hot-reloaded.

## Architecture

- `_config.yml` — site-wide settings (title, URL, theme, plugins)
- `_posts/` — blog posts, named `YYYY-MM-DD-title.markdown`
- `index.markdown`, `about.markdown` — top-level pages
- `404.html` — custom error page
- `Gemfile` — Ruby dependencies; use `bundle exec` for all Jekyll commands
- `.github/workflows/jekyll-gh-pages.yml` — CI/CD pipeline; builds and deploys to GitHub Pages on push to `main`

## Deployment

Pushing to `main` triggers the GitHub Actions workflow which builds and deploys to GitHub Pages automatically. No manual deploy step needed.
