# Data-Cleaning-Utility-
A professional data cleaning pipeline built with Python and Pandas to detect, fix, and validate a messy real-world e-commerce sales dataset.

🧹 Data Cleaning Utility — Project 3

Project Summary

This project builds a professional data cleaning pipeline using Python and Pandas,
applied to a real-world messy e-commerce sales dataset of 103 rows and 11 columns.

The dataset contained multiple quality issues including inconsistent category labels
(`electronics`, `ELECTRONICS`, `electronic`), non-numeric price values (`abd`,
`four hundred`, `300$`), negative and outlier prices, invalid quantities, an
unparseable date, 3 duplicate rows, and 15 total mismatches where `Total ≠ Price × Quantity`.

The pipeline resolves each issue systematically across 9 steps: standardizing column
names, fixing categories, cleaning price and quantity fields, parsing dates, imputing
missing values using category-level medians, recalculating totals from source columns,
and removing duplicates. Every action is recorded in a timestamped cleaning log.

The final output is a fully validated dataset of 99 rows × 14 columns with zero null
values, correct data types, and three bonus features extracted from the order date:
`order_year`, `order_month`, and `order_month_name`.

**Tools used:** Python, Pandas, NumPy, Google Colab, Claude AI
**Key skills:** Missing value imputation, dtype fixing, outlier detection, deduplication, feature engineering

 Google Colab Link: https://colab.research.google.com/drive/14mRlAYozqEZyRkMHZA33YJAIoUNH6G3-?usp=sharing
