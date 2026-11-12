# Exoplanet Dataset Column Cleaning

A pandas exercise that reduces an exoplanet catalogue to a smaller set of useful fields and renames selected columns for readability.

## Files

- `c130/dataset_1.csv` — source catalogue.
- `c130/main.py` — drops selected columns, renames retained fields, and writes `main.csv`.

## Requirements

```bash
pip install pandas
```

## Run

Run from the `c130` directory:

```bash
python main.py
```

The script tolerates source columns that are already absent and writes the output without a pandas index. The selected field list is based on the original exercise; review it against the dataset schema before using the reduced file for scientific analysis.