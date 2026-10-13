# Data

This folder is for data documentation and small, openly licensed examples only. Raw or large datasets should stay out of Git.

## Sources to verify

- Soil moisture: https://www.data.gov.in/catalog/soil-moisture
- Rainfall context and datasets: https://mausam.imd.gov.in/

Before downloading, record the exact dataset page, access date, license/terms, units, time coverage, and geographic level. Verify that soil-moisture and rainfall records can be aligned at a defensible district/state and time resolution. The project should document any mismatch instead of forcing an unreliable join.

Place local raw files under `data/raw/` and derived files under `data/processed/`; these paths are ignored by Git.
