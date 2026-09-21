# IGNIS Data Store

Harmonized fire-climate data produced by the IGNIS pipeline (NASA Space Apps 2026,
challenge #9). **Private during judging.**

## Contents
- `calendar_<region>.json` — 9 regional 25-year harmonized MODIS+VIIRS monthly
  calendars (2000-11 → 2026-09), per-sensor with harmonization ratios
- `analysis/ignis_calendar_long.csv` — long-format unified calendar (5,022 region-months)
- `analysis/ignis_emissions_estimates.csv` — FRE-derived CO2e emissions (tau = 1800 s,
  calibrated against published Amazon-2024 estimates)
- `analysis/ignis_regime_matrix.csv` — 9-region fire-regime feature matrix
- `analysis/training_snapshot.csv` — 138k-detection multi-sensor training snapshot
  (Amazon/Congo/Borneo, 5 days, 5 sensors)
- `analysis/ignis_complexes_latest.csv` + `complexes_summary.json` — DBSCAN complex stats

## Provenance
All data derives from NASA FIRMS active-fire detections (public domain) and NASA GIBS.
Harmonization methodology in the main repo: https://github.com/Hisernberg/ignis-spaceapps2026
