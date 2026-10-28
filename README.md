# VEDA Technology — Task 13: Duplicate Record Check

## Project Overview
This project focuses on identifying duplicate customer records, documenting data-quality issues, and preparing a cleaned copy of the dataset as part of VEDA Technology's Data Analytics internship tasks.

## Objectives
- Identify exact duplicate rows using Pandas.
- Examine records belonging to duplicate groups.
- Understand how duplicate records affect data accuracy and business metrics.
- Create a duplicate report and a cleaned dataset.
- Maintain an audit trail of data-cleaning decisions.

## Dataset
**Dataset:** Dirty Customers

The dataset contains 11 columns:
- `customer_id`
- `full_name`
- `email`
- `age`
- `order_amount`
- `account_status`
- `country`
- `signup_date`
- `notes`
- `unused_flag`
- `region`

## Tools and Technologies
- Python
- Pandas

## Methodology
1. Loaded the customer dataset.
2. Inspected the dataset structure and column names.
3. Identified exact duplicate rows using Pandas.
4. Examined rows belonging to duplicate groups.
5. Removed exact duplicate rows while preserving the first occurrence.
6. Prepared a duplicate report and a separate cleaned copy.
7. Documented the cleaning process for reproducibility.

## Key Finding
- **Rows involved in duplicate groups:** 1,332

This figure includes all rows belonging to duplicate groups, including the first occurrence. It does not represent the number of rows removed. The exact duplicate count and final cleaned row count should be recorded from the verified cleaning output.

## Deliverables
- Duplicate report
- Cleaned customer dataset
- Data-cleaning audit note

## Interview Questions

**1. What is a duplicate row?**

A duplicate row is a record that repeats another record across all columns or selected key columns, depending on the criteria used.

**2. How can duplicates affect totals?**

Duplicates can inflate sales, revenue, order counts, and other metrics, resulting in inaccurate calculations and misleading business insights.

## Learning Outcomes
- Practiced duplicate detection with Pandas.
- Learned the difference between duplicate-group membership and exact duplicate counts.
- Understood the importance of preserving original data and documenting cleaning decisions.
- Strengthened practical data-quality assessment skills.

## Acknowledgment
Completed as part of VEDA Technology's Data Analytics internship task series.
