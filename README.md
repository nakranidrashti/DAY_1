# ML Data Preprocessing Tasks

## Description

This repository contains three data preprocessing tasks implemented using Python, Pandas, NumPy, and Jupyter Notebook.

The tasks focus on preparing a dataset for machine learning by handling missing values, removing redundant data, and standardizing column names and data types.

## Dataset

**Dataset:** Women's Clothing E-Commerce Reviews

**Source:** Kaggle

The dataset contains customer reviews and information related to women's clothing products, including ratings, recommendations, feedback counts, divisions, departments, and classes.

## Tasks Completed

### Task 1: Missing Value Handling

* Identified missing values in the dataset.
* Analyzed missing values column by column.
* Handled missing values using an appropriate strategy based on the available data.
* Removed 14 records with missing `Class Name` because a reliable value could not be recovered from the available information.
* Verified that the required missing-value handling was completed.

### Task 2: Data Cleaning

* Detected duplicate rows automatically.
* Removed completely duplicated rows without removing valid records with the same `Clothing ID`.
* Automatically detected potentially irrelevant columns.
* Identified empty, unnamed, and constant-value columns.
* Added protection for important columns to reduce the risk of losing critical information.
* Implemented a cleaning log to record the operations performed.
* Compared the dataset before and after cleaning.

### Task 3: Data Standardization

* Standardized column names dynamically.
* Converted column names to lowercase.
* Replaced spaces and special characters with underscores.
* Removed unnecessary underscores from column names.
* Dynamically checked object columns for numeric-compatible values.
* Safely converted compatible values to appropriate numeric data types.
* Detected boolean-like values and converted them where appropriate.
* Used safe conversion methods to avoid unnecessary data loss.
* Logged column-name and data-type conversions.
* Verified the final dataset structure and data types.

## Technologies Used

* Python
* Pandas
* NumPy
* Regular Expressions
* Jupyter Notebook

## Project Structure

```text
DAY_1/
│
├── README.md
├── task1.ipynb
├── task2.ipynb
├── task3.ipynb
├── cleaned_womens_clothing.csv
└── standardized_womens_clothing.csv
```

## File Description

| File                               | Description                               |
| ---------------------------------- | ----------------------------------------- |
| `task1.ipynb`                      | Missing value handling                    |
| `task2.ipynb`                      | Duplicate and irrelevant data removal     |
| `task3.ipynb`                      | Column name and data type standardization |
| `cleaned_womens_clothing.csv`      | Dataset generated after Task 2            |
| `standardized_womens_clothing.csv` | Dataset generated after Task 3            |
| `README.md`                        | Project documentation                     |

## Data Preprocessing Workflow

```text
Original Dataset
       |
       v
Missing Value Handling
       |
       v
Duplicate & Irrelevant Data Detection
       |
       v
Column Name Standardization
       |
       v
Data Type Correction
       |
       v
Final Preprocessed Dataset
```

## Key Learning Outcomes

Through these tasks, the following data preprocessing concepts were implemented:

* Missing value handling
* Duplicate detection
* Data cleaning
* Irrelevant column detection
* Data integrity protection
* Column name standardization
* Data type validation
* Safe data type conversion
* Data preprocessing automation
* Logging of preprocessing operations

## Author

**Drashti Nakrani**
