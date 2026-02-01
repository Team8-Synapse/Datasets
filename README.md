# Student Placement Test Dataset 🎓

## Overview
This repository contains a synthetic dataset (`test_dataset.csv`) representing university student placement records. It is designed for testing data analysis workflows, SQL queries, Excel dashboards, and machine learning preprocessing pipelines.

The data mimics a realistic university scenario with specific batch structures, placement statuses, and auto-generated institutional emails.

## File Information
* **File Name:** `test_dataset.csv`
* **Format:** CSV (Comma Separated Values)
* **Total Records:** 300 rows
* **Total Columns:** 5

## Data Dictionary
| Column Name | Data Type | Description | Example |
| :--- | :--- | :--- | :--- |
| `name` | String | Randomly generated full name (Indian context). | `Aarav Sharma` |
| `roll_number` | String | Unique student identifier. | `CB.SC.U4CSE22001` |
| `placed` | String | Status of placement (`Yes` / `No`). | `Yes` |
| `company` | String | Recruiting company. **Null/Empty** if `placed` is 'No'. | `Google` |
| `email` | String | Institutional email derived from the roll number. | `cb.sc.u4cse...` |

## Data Logic & Batches
The dataset simulates **5 distinct batches** of 60 students each, with intentional gaps in the roll number series to test data handling logic.

### Roll Number Ranges:
1.  **Batch 1:** `CB.SC.U4CSE22001` to `...22060`
2.  **Batch 2:** `CB.SC.U4CSE22101` to `...22160` (Gap of 40 IDs)
3.  **Batch 3:** `CB.SC.U4CSE22201` to `...22260` (Gap of 40 IDs)
4.  **Batch 4:** `CB.SC.U4CSE22301` to `...22360` (Gap of 40 IDs)
5.  **Batch 5:** `CB.SC.U4CSE22401` to `...22460` (Gap of 40 IDs)
