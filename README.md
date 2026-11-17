# wa-ev-data

Parquet copy of the **Electric Vehicle Title and Registration Activity** dataset from the Washington State Department of Licensing, for a Malloy class assignment.

- **Source:** https://data.wa.gov/Transportation/Electric-Vehicle-Title-and-Registration-Activity/rpr4-cgyd (Washington State open data)
- **Downloaded:** November 17, 2026
- **Rows:** 1,926,507 title and registration transactions (January 2010 to September 30, 2026), 33 columns
- **File:** `ev_title_registration_zstd.parquet` (Parquet v2, zstd compression, 30.2 MB; the original CSV is 933.8 MB), attached to release `v1.0`
- Column names were normalized to snake_case with DuckDB (`normalize_names=true`). Otherwise the data is unchanged.
