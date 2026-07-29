# closeable-comics-feed

Public daily gallery of [Closeable](https://github.com/pratkuk/writers-room) comic strips —
the ones that survived the autonomous pipeline's comedy + visual QA gates on their way to
Instagram.

- `index.html` — the gallery (GitHub Pages).
- `data/strips.json` — baked daily by `.github/workflows/update-feed.yml` from the
  factory-hub's public-safe `/api/comics/feed` (needs the `COMICS_WORKER_SECRET` repo
  secret; panel PNGs are public Vercel Blob URLs).

Pipeline home: factory-hub `/comics` (private) · writers-room `comic-daily` workflow.
