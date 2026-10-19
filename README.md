# MoS₂ Growth Loop — board

One number per growth run, so everyone can see the trend.

## Adding a run

Edit `data.csv` (on GitHub: open the file → pencil icon → add a line → Commit). The page updates within a minute or two.

```
date,run,value,metric_version,note
2026-10-21,059,180,v0,
```

- `date` — run date, `YYYY-MM-DD`
- `run` — the lab's run number
- `value` — the metric, in the unit shown on the board; leave empty if it could not be measured
- `metric_version` — the metric definition used (see the top of `index.html`)
- `note` — optional, short (e.g. `repeat of best`)

Only numbers here. Images, temperature programs and discussion stay elsewhere.

## Changing the metric

Only after the weekly meeting agrees. Update `METRIC` in `index.html`, bump the version, and recompute earlier runs under the new definition so the curve stays comparable.
