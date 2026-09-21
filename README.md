# Boone County Dispatch: 2021–22 vs. 2025–26

This repository compares two approximately one-year Boone County dispatch datasets.

- **2021–22:** 2021-09-03 through 2022-09-03
- **2025–26:** 2025-08-12 through 2026-08-05

## Repository contents

### data
- `dispatch_2021-09-03_to_2022-09-03.csv`
- `dispatch_2025-08-12_to_2026-08-05.csv`
- `period_summary.csv`
- `call_type_comparison.csv`
- `ward_comparison_resolved_only.csv`

### docs
- `data_dictionary.csv`
- `methodology.md`

## Geography rule

Ward and precinct are assigned from address, not police beat. Police beat is retained only as an observed dispatch field.

For 2021–22, **15,385 of 89,262 records (17.2%)** matched an address in the current master crosswalk. The rest remain `Unresolved`.

## Comparison cautions

- The periods cover 366 and 359 days, so comparison tables include annualized rates.
- Dispatch category definitions may have changed. Large changes such as `TRESPASSING` should be checked for coding changes before interpretation.
- The older source did not include the derived `Crime-related` flag, so that field is blank in the standardized 2021–22 file.
- Ward comparisons are provisional where older addresses remain unresolved.
