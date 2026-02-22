# Personal Site Spec

## Goal
Build a minimal, single-page personal site for Devon Peroutky using plain HTML + Tailwind CDN (no build step), deployed to GitHub Pages at `DevonPeroutky.com`.

## Design Requirements
- Tailwind via CDN (`<script src="https://cdn.tailwindcss.com?plugins=typography">`)
- Inline `tailwind.config` for dark mode (`class` strategy) + custom colors
- Clean, minimal layout: centered content, generous whitespace
- Mobile responsive via Tailwind utilities
- Dark/light mode toggle with small inline JS
- Semantic HTML5 (`<header>`, `<main>`, `<section>`, `<footer>`)
- Accessible: proper contrast, aria labels, focus-visible states

## Sections
- Name / tagline (placeholder bio)
- Social links
- Optional projects section

## Links
- GitHub: `https://github.com/DevonPeroutky/`
- LinkedIn: `https://www.linkedin.com/in/devon-peroutky-806748146`
- Website: `devonperoutky.com`

## Deployment
- GitHub Pages from `main` branch
- Custom domain: `DevonPeroutky.com`
- CNAME file for GitHub Pages
- DNS: A records pointing to GitHub's IPs + CNAME `www` -> `devonperoutky.github.io`

## Files
| File | Purpose |
|------|---------|
| `index.html` | Single-page site |
| `CNAME` | Custom domain for GitHub Pages |
| `css/custom.css` | Minimal custom styles |
