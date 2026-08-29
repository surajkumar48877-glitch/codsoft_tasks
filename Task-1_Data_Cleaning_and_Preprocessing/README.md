# Customer Shopping Trends — Data Cleaning & Preprocessing

## Overview
A professional Task 1 data-cleaning project using Python and Pandas.

## Objective
Prepare customer shopping data for reliable analysis by identifying and resolving common data-quality issues.

## Dataset
- Original size: **3,900 rows × 19 columns**
- Domain: Customer shopping / sales behavior

## Tools
Python, Pandas, NumPy, Matplotlib, Jupyter Notebook, CSV

## Issues Demonstrated
The raw dataset is preserved unchanged. A separate practice copy demonstrates:
- 4 missing values
- 3 duplicate records
- inconsistent capitalization
- extra whitespace
- datatype correction for `Age`

## Cleaning Methods
1. Import and inspect the raw CSV.
2. Check missing values and duplicates.
3. Inspect categorical values.
4. Fill missing numerical values with the median.
5. Remove duplicate records.
6. Standardize categorical text with `strip()` and `title()`.
7. Convert `Age` to integer.
8. Validate the cleaned dataset.
9. Export `cleaned_dataset.csv`.

## Final Result
- Rows: **3,900**
- Columns: **19**
- Missing values: **0**
- Duplicate records: **0**
- `Age`: **int64**
- `Review Rating`: **float64**

## Structure
```text
Task_1_Data_Cleaning/
├── data/
│   ├── shopping_trends.csv
│   └── shopping_trends_dirty.csv
├── notebooks/
│   └── data_cleaning.ipynb
├── output/
│   └── cleaned_dataset.csv
├── README.md
└── requirements.txt
```

## How to Run
Open `notebooks/data_cleaning.ipynb` in Jupyter Notebook or VS Code and run the cells from top to bottom.
