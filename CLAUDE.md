# AGENTS.md

## Overview

GitHub Pages site with Jekyll/Minima theme. Publishes to <https://philoserf.github.io>.

## Structure

- `_config.yml` - Jekyll configuration
- `README.md` - Site homepage

Changes pushed to main auto-deploy via GitHub Pages.

## Making Changes

- **Content:** Edit `README.md`
- **Config:** Edit `_config.yml`

## Linting

```bash
bunx prettier --write <file>
```

## Local Preview

```bash
gem install github-pages
jekyll serve
```

Available at <http://localhost:4000>
