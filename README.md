# swedlines-content

Data and published site for [Swedlines](https://swedlines.com), a dual-language (Swedish / English) aggregator of Swedish news headlines.

- `content/YYYY/MM/DD/<id>.json` — one file per headline, written by the pipeline in [nevenc/swedish-news-app](https://github.com/nevenc/swedish-news-app).
- `docs/` — generated static site, JSON API, feeds, and ticker, served by GitHub Pages at https://swedlines.com.

Every commit here is made by the pipeline. Do not edit by hand; change `sources.yaml` or the code in the app repo instead.
