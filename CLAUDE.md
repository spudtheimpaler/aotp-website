# CLAUDE.md

This file provides guidance for development in this repository.

## Project Overview

Static website for Andrew Easton, a prominent radio DJ and pianist. Hosted via GitHub Pages from the `docs/` directory, served at `andrewonthepiano.com` (or `.co.uk`).

## Architecture

- **Single-page static site** — all content lives in `docs/index.html` (HTML + inline CSS, no build step)
- **`docs/`** — GitHub Pages root; contains `index.html`, `CNAME`, and image/media assets
- **No build tools, no JavaScript, no package manager** — edit HTML/CSS directly

## Deployment

Pushing to `main` deploys automatically via GitHub Pages. The `docs/` folder is the publish source.

## Design Tokens

- **Piano Black:** `#121416` (Deep slate black used for text, dark mode blocks, and strong contrast)
- **Ivory Cream:** `#faf8f5` (Warm off-white/cream for backgrounds, offering a softer look than pure white)
- **Brass Gold:** `#c5a059` (Muted brassy gold for accents, key borders, and secondary highlights)
- **Heading font:** 'Playfair Display' or 'EB Garamond' (Google Fonts)
- **UI/Nav font:** 'Montserrat' or 'Outfit' (Google Fonts)
- **Body font:** System font stack (clean sans-serif)
