# Task 1 — Data Cleaning & Preprocessing  
**Dataset:** Netflix Movies and TV Shows (cleaned)

## Objective
Clean and prepare the raw Netflix dataset by handling missing values, duplicates, inconsistent formats, and ensuring proper data types. Deliverables: cleaned dataset + short summary.

## Files included
- netflix_titles_cleaned.csv — cleaned dataset (final)

## Summary of cleaning steps performed
1. Loaded dataset and created working copy.
2. Handled missing values:
   - director: Unknown
   - cast: Not Provided
   - country: Unknown
   - rating: Not Rated
3. Standardized text using TRIM, PROPER, UPPER
4. Fixed date_added → dd-mm-yyyy
5. Split duration into:
   - duration_value (number)
   - duration_unit (text)
6. Removed duplicates (0 found)
7. Renamed columns:
   show_id, type, title, director, cast, country, date_added,
   release_year, rating, duration, duration_value,
   duration_unit, listed_in, description

## Final statistics (verified)
- Rows: 8807
- Columns: 14
- Missing values remaining: duration (3)
- Duplicates removed: 6

## Conclusion
Dataset is cleaned and ready for analysis.
