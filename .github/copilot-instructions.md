# GitHub Copilot Instructions

## Project Overview

This is a personal portfolio website for Nishtha Sethi, a Software Engineer and MSc Computer Science student. The site is built as a single-page static HTML application hosted on GitHub Pages at https://sethinishtha.github.io/.

## Repository Structure

- `index.html` — The single-page portfolio website (HTML, CSS, and JavaScript all in one file)
- `189302053_NishthaSethi.JPG` — Profile photo used in the portfolio
- `NishthaSethi_CV.pdf` — Downloadable CV/resume linked from the portfolio
- `README.md` — Project description

## Technology

- **HTML5** with inline CSS and JavaScript (no build step required)
- **typed.js 2.1.0** (via CDN) for the animated typing effect in the header
- **GitHub Pages** for static hosting

## Coding Conventions

- All styles are written inline within `<style>` tags in `index.html`
- All JavaScript is written inline within `<script>` tags at the bottom of `index.html`
- Dark-themed colour palette: primary background `#0a0e27`, accent colours `#00d4ff` and `#7b2cbf`
- CSS uses `#e0e0e0` for primary text colour on dark backgrounds
- No external CSS frameworks or JavaScript libraries other than typed.js are used
- External resources are loaded via CDN (cdnjs.cloudflare.com)

## External Dependencies

| Library   | Version | CDN URL                                                               |
|-----------|---------|-----------------------------------------------------------------------|
| typed.js  | 2.1.0   | https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.1.0/typed.umd.js  |

## Notes for Copilot

- Keep changes self-contained within `index.html` unless adding new assets
- Maintain the existing dark colour scheme when adding or modifying sections
- Preserve the single-file approach — avoid introducing a build pipeline unless explicitly requested
- When updating CDN library versions, verify the new URL resolves correctly on cdnjs.cloudflare.com
