Project 2: Data Cleaning in Pandas

Understanding the Task:
Cleaned and prepared a messy dataset for analysis using pandas.

Steps Performed:

1.Handling Missing Data:
Identified missing values using .isnull() and .sum().
Imputed missing values using .fillna() or dropped them with .dropna() based on the context.

2.Fixing Data Types:
Converted columns to appropriate types using .astype() or pd.to_datetime() (e.g., dates, numerical values).

3.Standardizing Columns:
Renamed columns for consistency using .rename() or .columns.
Removed extra spaces and ensured uniform capitalization.

4.Removing Duplicates:
Checked for duplicate rows using .duplicated() and removed them with .drop_duplicates().

5.Outlier Treatment:
Identified outliers using the Interquartile Range (IQR) method.
Handled outliers by capping, removing, or flagging them.

6.Feature Engineering:
Created new columns or derived metrics (e.g., total sales from unit price and quantity).

7.Outcome:
Delivered a clean, consistent, and ready-to-analyze dataset, minimizing errors and improving usability for analysis.
