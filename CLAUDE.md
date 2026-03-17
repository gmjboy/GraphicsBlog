# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

GraphicsBlog - A VitePress-based documentation/blog site exploring graphics systems from rendering to display.

## Commands

```bash
pnpm docs:dev     # Start local development server
pnpm docs:build   # Build static site for production
pnpm docs:preview # Preview production build locally
```

## Architecture

- **Framework**: VitePress (Vue-based static site generator)
- **Package Manager**: pnpm (v10.11.0)
- **Config**: `docs/.vitepress/config.mts` - site configuration with theme, navigation, and sidebar
- **Content**: Markdown files in `docs/` directory
  - `docs/index.md` - Home page
  - `docs/markdown-examples.md` - Markdown feature demos
  - `docs/api-examples.md` - Vue runtime API examples

## Content Structure

VitePress uses file-based routing - each `.md` file in `docs/` becomes a route. Place new posts/pages in `docs/` and update `sidebar` in `config.mts` for navigation.
