# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Is

**IB_OS** is a single-page personal brand/portfolio site for Ignacio Bermúdez. It is a pure static HTML file — no build tools, no package manager, no JavaScript framework, no dependencies to install.

The main deliverable is `index.html`, which is served directly by any static host (e.g. GitHub Pages).

## Repository State

- The canonical branch for the live site is **`index.html`**
- `index.html` on that branch currently holds only a placeholder (the literal text `index.html`)
- The intended full HTML design lives in **`README.md`** wrapped in a fenced code block — that HTML is what `index.html` should actually contain

## How to Preview

There is no build step. Open `index.html` directly in a browser, or serve it with:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Architecture

Everything is a single `index.html` file. No other source files, assets, or scripts.

**Styling**: Tailwind CSS loaded from CDN (`https://cdn.tailwindcss.com`). All utility classes are applied inline; there is no separate stylesheet.

**Custom CSS** (inlined `<style>` block):
- `body` — background `#050505`, `Inter` sans-serif
- `.mono` — `Fira Code` monospace; used for all terminal-style text
- `.gradient-text` — white-to-gray horizontal gradient via `-webkit-background-clip`
- `.terminal-box` — dark-bordered card with semi-transparent black background

**Fonts**: Google Fonts CDN — `Fira Code` (weights 300, 500) and `Inter` (weights 400, 800).

**Color palette**: zinc scale (`zinc-400`, `zinc-500`, `zinc-600`, `zinc-800`, `zinc-950`), `red-600` for section headings, `#050505` page background.

## Content Conventions

- All copy is in **Spanish**
- Section anchors: `#manifiesto`, `#promis`, `#archivo`
- Headings use `.mono` with `uppercase tracking-widest text-sm text-red-600` style
- Status/metadata lines use the pattern `> KEY: VALUE` in a `<ul class="mono text-xs">`
- Contact is `mailto:ignacio@ib-os.com`
