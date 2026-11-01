# Duplicate Data Removal

**Internship Task 23 | Python and Pandas**

## Project Overview

This project focuses on identifying and removing duplicate records from a dataset using Python and the Pandas library. The process helps improve data quality and maintain accurate information for further analysis.

## Objective

- Identify duplicate records in a dataset.
- Count the total number of duplicate records.
- Remove repeated records using Pandas.
- Compare the dataset before and after cleaning.
- Export the cleaned dataset as a CSV file.

## Technologies Used

- Python
- Pandas
- Jupyter Notebook
- CSV

## Project Structure

```text
Task_23_Duplicate_Data_Removal/
│
├── Duplicate_Data_Removal.ipynb
├── cleaned_dataset.csv
└── README.md
```

## Implementation Steps

1. Import the Pandas library.
2. Create a sample dataset containing duplicate records.
3. Convert the dataset into a DataFrame.
4. Identify duplicate records using `duplicated()`.
5. Calculate the number of duplicate records.
6. Remove duplicates using `drop_duplicates()`.
7. Compare the original and cleaned datasets.
8. Export the cleaned dataset using `to_csv()`.

## Results

| Description | Result |
|---|---:|
| Original records | 8 |
| Duplicate records identified | 2 |
| Records after cleaning | 6 |
| Records removed | 2 |

## How to Run

1. Open `Duplicate_Data_Removal.ipynb` in Jupyter Notebook or VS Code.
2. Install Pandas if required using `pip install pandas`.
3. Run all notebook cells.
4. The cleaned dataset will be generated as `cleaned_dataset.csv`.

## Conclusion

The task successfully demonstrates duplicate detection and removal using Pandas. Two duplicate records were identified and removed, resulting in a cleaned dataset containing six unique records.

## Key Learning

Gained practical experience in data cleaning, duplicate detection, DataFrame manipulation, and exporting cleaned datasets using Python Pandas.