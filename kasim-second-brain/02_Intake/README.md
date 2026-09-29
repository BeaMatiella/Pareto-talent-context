# 02_Intake

Pipeline for mined material.

- `raw/` — untouched originals (transcripts, exports, scraped pages). Never edit.
- `processed/` — cleaned markdown versions ready to feed into `01_Context/` or `04_Knowledge/`.
- `intake-log.md` — one row per item ingested.

Flow: raw -> processed -> distilled into Context/Knowledge -> logged.
