# apricity

A public diary by Ahmed Bin Asim, built with [Astro](https://astro.build).

```sh
npm install
npm run dev     # local dev server
npm run build   # static build into dist/
```

Entries live in `src/content/blog/` as Markdown. The RSS feed is generated at `/rss.xml`.

Before deploying, set `site` in `astro.config.mjs` to the real URL. It is still the placeholder `https://example.com`, which RSS, the sitemap and canonical links all use.
