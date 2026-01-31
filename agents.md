# Agents

Guidelines for AI agents working on this repository.

## Project Overview

Static portfolio website for **Jonathan Manfield / Dense Kernel**.

- Hosted on GitHub Pages
- Published directly from `main` branch
- URL: densekernel.github.io/densekernel (or custom domain if configured)

## Core Principles

### Minimalism
- Less is more. Avoid unnecessary complexity.
- Prefer native HTML/CSS over frameworks.
- No build step required unless absolutely necessary.

### Simplicity
- Code should be readable without deep context.
- Flat file structure when possible.
- Semantic HTML over div soup.

### Easy to Manage
- Single-file changes preferred over multi-file edits.
- Inline styles acceptable for one-off elements.
- No dependencies unless they provide significant value.

## Tech Stack

- **HTML** - Semantic, accessible markup
- **CSS** - Vanilla CSS, no preprocessors needed
- **JavaScript** - Vanilla JS only if needed, keep it minimal

## Workflow

1. All changes go directly to `main`
2. GitHub Pages auto-deploys on push
3. No staging branch, no PRs required for solo work

## File Structure (Target)

```
/
├── index.html      # Main landing page
├── style.css       # Global styles (optional, can be inline)
├── assets/         # Images, fonts if needed
├── README.md       # Repo description
└── agents.md       # This file
```

## Style Guidelines

- Dark/light theme optional, but keep it simple
- Typography: system fonts preferred for performance
- Mobile-first responsive design
- Fast load times over visual complexity

## What to Avoid

- Heavy frameworks (React, Vue, etc.)
- CSS frameworks (Bootstrap, Tailwind)
- Build tools (webpack, vite) unless justified
- Over-engineering for a simple portfolio
- Excessive comments - code should be self-documenting
