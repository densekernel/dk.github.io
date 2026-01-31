# Agents

Guidelines for AI agents working on this repository.

## Project Overview

Static portfolio website for **Jonathan Manfield / Dense Kernel**.

- Hosted on GitHub Pages
- Published directly from `main` branch
- URL: densekernel.github.io/densekernel (or custom domain if configured)

## Core Principles

### Simplicity
- Keep code readable and straightforward
- Prefer flat file structures where practical
- Semantic HTML is encouraged

### Maintainability
- Lean towards single-file changes when reasonable
- Inline styles are fine for one-off elements
- Add dependencies only when they add clear value

## Tech Stack

- **HTML** - Semantic, accessible markup
- **CSS** - Vanilla CSS preferred
- **JavaScript** - Vanilla JS when needed

## Workflow

1. Changes go directly to `main`
2. GitHub Pages auto-deploys on push

## File Structure

```
/
├── index.html      # Main landing page
├── style.css       # Global styles (optional)
├── assets/         # Images, fonts if needed
├── README.md       # Repo description
└── agents.md       # This file
```

## Style Guidelines

- Dark theme with clean typography
- System fonts for performance
- Responsive design
- Prioritise fast load times

## Preferences

- Vanilla HTML/CSS/JS over frameworks when practical
- Avoid heavy build tooling unless justified
- Keep it simple, but don't sacrifice user experience
