# mainpage-hydroloopfarm

Landing page for **HydroLoop Farm** — a Moroccan modular A-Frame NFT growing system with a companion seed-to-batch tracking app.

- `index.html` — main English landing page (served at https://hydroloopfarm.com via GitHub Pages)
- `hydroloop-farm-bilingue.html` — earlier bilingual FR/EN page, linked from the footer
- `assets/` — images used by the page
- `index.md` — full page content as Markdown, for AI agents and LLMs
- `llms.txt` — short machine-readable summary and key links ([llmstxt.org](https://llmstxt.org))
- `robots.txt`, `sitemap.xml` — crawler access (AI agents explicitly allowed) and page list
- `.nojekyll` — serve files as-is on GitHub Pages (keeps `index.md` raw)

`index.html` also embeds schema.org JSON-LD (Organization, Person, Product, SoftwareApplication, FAQPage). Keep it, `index.md` and `llms.txt` in sync when the content changes.

Static HTML/CSS/JS, no build step.
