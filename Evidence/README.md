
# IG-First Dataset (v4)

- Prefers Instagram URLs when posts exist across multiple platforms.
- Non-Instagram included only if no IG version exists (e.g., Two-state framing video on Facebook).
- Evidence stored in `evidence.csv` and `site_data.json`.
- `screenshots/` and `archives/` contain placeholders to be replaced with actual screenshots and archive links.

## Workflow
1. Add new Instagram links to `evidence.csv` as they appear.
2. Replace screenshot placeholders with captures (include handle, timestamp, caption).
3. Add archive.today/Perma.cc links into the `.txt` placeholders or `archived_url` column.
4. `site_data.json` is ready for your site (place at `public/data/evidence.json`).
