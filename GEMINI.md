# aeo-demo-wedding

## Overview
AEO (AI-Engine Optimization) demo template tailored for the wedding industry. It showcases how to structure HTML content, generate `llms.txt`, and implement Schema.org markup to ensure maximum visibility for AI agents and search engines.

## Tech Stack
- **Core**: HTML5
- **SEO/AEO**: JSON-LD (Schema.org), Open Graph, Twitter Cards
- **AI Integration**: llms.txt, FAQ markup
- **Styling**: CSS3 (Minimal/Responsive)

## Architecture
- `index.html`: Main landing page with semantic structure.
- `llms.txt`: Text-based sitemap for LLM consumption.
- `faq.html`: Dedicated FAQ section optimized for AI context windows.
- **Data**: JSON-LD scripts embedded for "WeddingEvent", "Product", and "FAQPage".

## Commands
- **Preview**: Open `index.html` directly in a browser or use a simple server (e.g., `python3 -m http.server`).
- **Deployment**: Deploy to any static host (GitHub Pages, Vercel, Netlify).
- **Validation**: Use Google's Rich Results Test to validate Schema.org markup.

## Coding Style
- **Semantic HTML**: Use `<main>`, `<article>`, `<section>`, and `<header>` for clear document outline.
- **Accessibility**: Ensure high contrast and ARIA labels where necessary.
- **Schema**: Always validate JSON-LD using a linter before deployment.

## Important Rules
- **No Blocking**: Do not use `robots.txt` to disallow AI bots (GPTBot, Google-Extended).
- **Content Sync**: Keep the content in `llms.txt` synchronized with the actual site content.
- **Structure**: Prioritize clear, direct answers in text content to improve chances of being used by LLMs.