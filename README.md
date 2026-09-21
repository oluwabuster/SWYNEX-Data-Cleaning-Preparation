# SWYNEX-Data-Cleaning-Preparation

## Dataset
- Name: Titanic Dataset
- Source: Kaggle Titanic Competition

## Problems Identified
- Age: 177 missing values
- Cabin: 687 missing values
- Embarked: 2 missing values
- No duplicate rows found

## Cleaning Steps
1. Filled missing Age values with the median age
2. Filled missing Embarked values with the most frequent value (mode)
3. Dropped the Cabin column (too many missing values)
4. Removed any duplicate rows
5. Standardized the Sex column

## Tools Used
- Python (Pandas)
- Google Colab

## Files
- `cleaned_titanic.csv` → Cleaned dataset
