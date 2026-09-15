# Task for Spaces website agent guidance

- Always write `500nits` in lowercase.
- This repository publishes `https://task.500nits.com/`. Keep `CNAME`, canonical tags, internal links, `robots.txt`, and `sitemap.xml` on that exact HTTPS origin.
- When this repository is checked out inside the 500nits hub workspace, read `../AGENTS.md`, `../.agents/SITES.md`, and `../.agents/SEO.md` before website work. Read `../.agents/SEARCH_CONSOLE.md` before Search Console work.
- Treat every public HTML page as intentionally indexable or explicitly `noindex`. Include only canonical, indexable pages in `sitemap.xml`.
- Before deploying from the hub workspace, run `node ../scripts/audit-seo.mjs`.
- Preserve unrelated changes. Commit and push this repository directly; the hub repository ignores this checkout.
