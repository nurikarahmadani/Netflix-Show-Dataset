# Netflix Show Dataset

## Data Source
[https://www.kaggle.com/datasets/infamouscoder/dataset-netflix-shows](https://www.kaggle.com/datasets/infamouscoder/dataset-netflix-shows)<br>

## 🎯 Objective
The objective of this project is to clean and prepare the Amazon Sales dataset by resolving data quality issues such as missing values, inconsistent formatting, duplicate records, and unstructured text fields to ensure the dataset is reliable for analysis.

## Dataset Information
* **File Format** : CSV
* **Total Columns** : 12 Columns
* **Total Rows** : 8807

## Data Quality Assessment
* Missing values
* Inconsistent text
* Noise/unwanted characters
* Incorect Data Type

## Cleaning Objectives
* Remove missing/blank values
* Standardize text formatting
* Repair/convert data types

## Cleaning Methods and Process

**Tools :** Excel Function TRIM, PROPER, REMOVE DUPLICATES, POWER QUERY

## Data Cleaning Actions
| Step | Column       | Issue Found       | Action Taken            | Example                         |                      |
| ---- | ------------ | ----------------- | ----------------------- | ------------------------------- | -------------------- |
| 1    | product_name | Inconsistent text | TRIM + PROPER           | `" usb Cable "` → `"Usb Cable"` |                      |
| 2    | category     | Complex format    | Split using delimiter ` | `                               | Hierarchy normalized |
| 3    | price        | Blank values      | Removed 217 rows        | Valid records only              |                      |




Total rows after cleaning : 5700