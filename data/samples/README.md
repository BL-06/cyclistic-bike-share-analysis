# Browsable data samples

The CSV files in this folder are small excerpts pasted for the project showcase. GitHub can display CSV files directly in a readable table view.

## Files

| Folder | File | Description |
|---|---|---|
| `raw/` | `2025-04.csv` | Raw April 2025 excerpt |
| `raw/` | `2025-10.csv` | Raw October 2025 excerpt |
| `cleaned/` | `2025-04.csv` | Cleaned April 2025 excerpt |
| `cleaned/` | `2025-10.csv` | Cleaned October 2025 excerpt |

## Notes on interpreting the samples

- These are illustrative excerpts, not the full source datasets.
- The raw and cleaned excerpts are from the same named months, but the pasted excerpts do not contain the same ride IDs in the same order. Do not treat them as a row-by-row before-and-after comparison.
- In the raw excerpts, `started_at` and `ended_at` appear as time-only values (for example, `29:34.6`); the date is not present in the pasted sample. In the cleaned excerpts they are shown as formatted times. Explain the exact transformation and source date handling in your project documentation if the full workbook contains that information.
- Missing station values are represented as blank in the raw October excerpt and as `Missing` in the cleaned October excerpt.
- The cleaned excerpts included an empty, unnamed column. That empty column has been removed from the showcase CSVs. Other columns and supplied values are retained; the sparse summary columns are not reinterpreted here. If these are workbook-level summary statistics, consider documenting or separating them from ride-level fields in the final analysis.
- The sample data is provided for portfolio viewing only. Link to or include full data only if the source terms permit redistribution.

## Suggested next steps

1. Add the source-data citation and download instructions.
2. Describe each cleaning step and why it was performed.
3. Record validation checks, such as row counts and missing-value checks.
4. Add the published Tableau dashboard link and a screenshot to the project README.
