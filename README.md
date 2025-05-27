# Day 1
1. **Loaded the data** using `pandas`.
2. **Removed duplicates** using `.drop_duplicates()`.
3. **Renamed columns** to lowercase with underscores for clarity.
4. **Converted `date_added`** to proper `datetime` format.
5. **Handled missing values**:
   - Replaced missing `director`, `cast`, `country` with `'Unknown'`
   - Filled missing `rating` with the most common value
   - Dropped rows where `date_added` was still missing
6. **Standardized text fields**:
   - `type` and `country`: capitalized (title case)
   - `rating`: converted to uppercase
7. **Saved the cleaned dataset** as `netflix_cleaned.csv`.
