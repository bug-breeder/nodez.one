# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the nodez.one website - a platform showcasing useful apps and tools built to solve real problems. The site uses Hugo with the Hextra theme for a modern, responsive design.

**Philosophy**: "Small acts, giant impacts" - focusing on creating practical solutions to everyday problems.

## Development Commands

### Local Development
```bash
# Start development server
hugo server --port 1313 --buildDrafts

# Build for production
hugo --minify
```

### Site Structure
- `content/` - All site content (Markdown files)
  - `content/_index.md` - Homepage
  - `content/blog/` - Blog posts
  - `content/apps/` - App showcase pages
  - `content/docs/` - Documentation (can be used for app docs)
  - `content/about/` - About page
- `static/` - Static assets (images, files)
- `themes/hextra/` - Hextra theme (submodule)

## Key Configuration

### Hugo Configuration (`hugo.yaml`)
- Site title: "nodez.one"
- BaseURL: "https://nodez.one/"
- Theme: Hextra (via Hugo modules)
- Multi-language support enabled (EN, FA, JA, ZH-CN)

### Content Guidelines
- Keep messaging humble and honest
- Focus on solving real problems
- Avoid technical jargon or bragging
- Use simple, clear language

### Deployment
- Domain: nodez.one (managed via Porkbun)
- Ready for static hosting (GitHub Pages, Netlify, Vercel, etc.)

## Theme Features Available
- Hero sections with badges and buttons
- Feature grids and cards
- Full-text search
- Blog with tags and RSS
- Dark/light mode
- Responsive design
- Syntax highlighting
- Math support (LaTeX)
- Multiple shortcodes for rich content