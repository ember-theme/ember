# Ember Theme — Agent Guide

Ember is a warm, nearly monochrome color theme. One vivid coral accent (`#e08060`) against desaturated graphite. Three variants: dark, soft, light.

## Directories

| Path | What it is |
|------|-----------|
| `palette.json` | Single source of truth for all colors across all variants |
| `emacs/` | Doom Emacs port — three `.el` files (ember, ember-soft, ember-light) |
| `site/` | Marketing site — Next.js, lives at embertheme.com |
| `melpa/` | Fork of melpa/melpa, contains our MELPA submission recipe |
| `screenshots/` | Theme screenshots and logo SVG |

## Key facts

- All ports derive from `palette.json` — never hardcode colors elsewhere
- The Emacs port depends on `doom-themes`; it is not standalone vanilla Emacs
- MELPA PR is open at melpa/melpa — do not merge emacs/ changes that break the recipe build
- `site/` has its own `AGENTS.md` with Next.js-specific notes — read it before touching the site
