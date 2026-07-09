# tofesbim-verify

**Purpose only**: a static, read-only "report verification" page for the TofesBIM pitch deck's QR code. Nothing else belongs in this repo.

- `index.html` — static page, reads a `?t=TOKEN` query param, looks it up in `records.json`, shows a verified badge. No server, no backend, no external calls besides fetching `records.json` from this same site.
- `records.json` — a small, manually-curated list of demo report tokens. Only non-sensitive fields (doc id, date, standard/finding counts). No project names, no IFC/GLB data, no source code, no credentials — ever.

**Do not add**: source code from the main TofesBIM app, real customer project data, API keys/secrets, IFC/GLB files, or anything not directly needed to render this one page. This repo is intentionally minimal and disconnected from the live product for security reasons.
