# Soil Moisture and Monsoon Patterns in India

An exploratory data analysis (EDA) project to study how soil-moisture observations vary across Indian districts and how they relate to monsoon rainfall over time.

> **Current status:** Project scaffold. The analysis, charts, and findings have not been implemented yet.

## Questions to explore

- How do available soil-moisture indicators vary by district, season, and year?
- Where do rainfall and soil-moisture patterns move together or diverge?
- Are there notable regional or seasonal differences in the available observations?
- What limitations arise from missing data, inconsistent reporting periods, or differing geographic coverage?

## Planned workflow

1. Inspect source data and document definitions, units, time periods, and geographic coverage.
2. Clean dates and district/state labels; check duplicates, missing values, and outliers.
3. Summarize coverage before joining datasets. Match rainfall and soil-moisture observations only at a defensible geographic and time resolution.
4. Use descriptive statistics, distributions, seasonal comparisons, and correlation analysis.
5. Visualize the results in a Jupyter notebook with time-series, distribution, and state/district comparison charts.
6. Record findings and caveats without treating correlation as causation.

## Planned visualizations

Notebook charts may include missingness/coverage summaries, monthly or seasonal time series, distributions, district/state comparisons, and rainfall-versus-soil-moisture scatter plots when the datasets can be aligned appropriately. No dashboard is planned for the initial version.

## Data sources to investigate

- [Soil moisture catalogue, Open Government Data Platform India](https://www.data.gov.in/catalog/soil-moisture)
- [India Meteorological Department](https://mausam.imd.gov.in/)

Dataset availability, download terms, field definitions, and compatible geography/time granularity must be checked before analysis. Do not commit restricted or large raw datasets; document acquisition steps in `data/README.md`.

## Stack

Python, Jupyter Notebook, Pandas, NumPy, SciPy, Matplotlib, Seaborn.

## Run locally

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

The notebook and verified results will be added as the analysis is built.