# MoS₂ Growth Loop — board

A few numbers per growth run, so everyone can see the trend.

## Adding a run

Edit `data.csv` (on GitHub: open the file → pencil icon → add a line → Commit). The page updates within a minute or two.

```
date,run,coverage,size_um,thick_frac,tile_cv,metric_version,note
2026-10-21,059,0.12,28.5,0.114,1.29,v1,
```

- `date` — growth date, `YYYY-MM-DD` (not the date the images were taken)
- `run` — the lab's run number
- `coverage`, `size_um`, `thick_frac`, `tile_cv` — the metrics (fractions as 0–1); leave a cell empty if it could not be measured
- `metric_version` — the metric definitions used (see `METRICS` at the top of the script in `index.html`)
- `note` — optional, short (e.g. `repeat of best`)

Only numbers here. Images, temperature programs and discussion stay elsewhere.

## Changing the metric

Only after the weekly meeting agrees. Update `METRICS` and `VERSION` in `index.html`, bump the version, and recompute earlier runs under the new definition so the curve stays comparable.
