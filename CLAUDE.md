# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**IB_OS** is a static personal landing page for Ignacio Bermúdez — a ghostwriter and researcher. The site presents the "IB_OS v.2026" brand and the ongoing novel project "PROMIS", a technical thriller about espionage, OSINT, and cryptography.

## File Layout

There are only two files of note:

- **`README.md`** — Contains the actual site HTML inside a fenced code block (` ```html ... ``` `). This is the primary working file.
- **`index.html`** — Currently a placeholder (contains only the text `index.html`). If a live deployment is needed, the HTML from README.md should be copied here.

No build step, no package manager, no bundler. Edit the HTML directly.

## Technology Stack

- **Tailwind CSS** loaded via CDN (`https://cdn.tailwindcss.com`) — no config file, no purge step
- **Google Fonts**: `Fira Code` (monospace, weights 300/500) and `Inter` (body, weights 400/800), loaded via `@import`
- Vanilla HTML5, no JavaScript framework

## Design System

Three custom CSS classes defined in `<style>` inside `<head>`:

| Class | Purpose |
|---|---|
| `.mono` | Applies `Fira Code` monospace font |
| `.gradient-text` | White-to-gray horizontal gradient text (clip technique) |
| `.terminal-box` | Dark panel with a subtle `#222` border — used for the PROMIS project card |

Color palette: background `#050505`, text `#e5e5e5`, zinc scale (`zinc-400`, `zinc-500`, `zinc-600`, `zinc-800`, `zinc-950`) for secondary elements, `red-600` for section labels, `white` for interactive hover states.

Typography pattern: section headers use `.mono text-[color] text-sm uppercase tracking-widest` prefixed with `//`. Navigation and metadata use `.mono text-[10px]`.

## Content Sections

Three anchor sections in the page:

- `#manifiesto` — Writing manifesto in Spanish; literary prose paragraphs with a blockquote-style callout
- `#promis` — Terminal-style card describing the novel project; uses a two-column grid with a `.terminal-box` wrapper
- `#archivo` — Footer with location data and contact link (`ignacio@ib-os.com`)

All content is in **Spanish**.

## Workflow

No commands to run — open `README.md`, edit the HTML inside the code block, then copy the result to `index.html` for deployment. There is no linting, testing, or CI pipeline.
