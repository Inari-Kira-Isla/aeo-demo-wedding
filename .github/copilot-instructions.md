# aeo-demo-wedding

## Project
AEO (AI-Engine Optimization) demo template for wedding industry using HTML with Schema.org, llms.txt, and AI-friendly markup.

## Conventions
- Use semantic HTML5 elements
- Include proper meta tags for SEO and AI crawlers
- Add structured data using JSON-LD Schema.org vocabulary
- Maintain accessible markup with ARIA labels where needed
- Keep all code in a single HTML file per page

## Naming
- Use lowercase with hyphens for file names: `wedding-services.html`
- Use descriptive, keyword-rich names for schema entities
- Name FAQ sections clearly: `id="faq"` for anchor linking

## Architecture
- Single-page HTML structure with embedded CSS and minimal JS
- JSON-LD scripts placed in `<head>` for search engines
- llms.txt in root directory for AI crawler discovery
- FAQ section using `<details>` and `<summary>` elements
- Schema.org types: Organization, FAQPage, BreadcrumbList

## Commands
- No build commands required — edit HTML directly
- Validate HTML with W3C Validator
- Test structured data with Google's Rich Results Test

## Do Not
- Do not remove Schema.org JSON-LD blocks
- Do not delete llms.txt reference in meta tags
- Do not use client-side frameworks — keep it static HTML
- Do not break semantic structure of FAQ and breadcrumb sections