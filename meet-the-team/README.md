# Nilwerk website (version 1)

- `index.html`: 3D office, contact buttons, highlights. No backend.
- `three.min.js`: 3D library, keep next to `index.html`.
- `data/status.json`: the only file Nora updates. The page reads it on load.
- `assets/`: photos. If a file is missing, the page shows "Photo coming soon".

## status.json rules for Nora
- Keep the same keys. Update `updated` each time.
- Never name clients, prices, or private repository details.
- Photos: square-ish or 4:3, under 300 KB, named with lowercase words.
- Keep `highlights` to 2–4 short items.

## German text
Add a German twin next to any English text field, with the suffix `_de`, for example `summary_de`, `reason_de`, `title_de`, `text_de`, `caption_de`, `status_de`, `next_de`. If a twin is missing, the English text is shown in German mode too.
