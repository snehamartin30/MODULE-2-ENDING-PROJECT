# MODULE-2-ENDING-PROJECT

# ABC Company Data Analysis (Google Colab)

## Overview
A Python (`pandas`, `numpy`, and `matplotlib`) data analysis project on `ABCcompanydataset.csv` (**458 rows**) built in **Google Colab**.

## Preprocessing
* Uploaded `ABC Company Dataset.csv` to Colab and checked dataset shape, columns, data types, and missing values (`isnull().sum()`).
* Randomized `Height` values between **150 and 180** and checked min/max values.

## Tasks & Charts
1. **Team Distribution:** Counted employees and percentages per team (`value_counts()`), plotted a bar chart (`plt.bar`).
2. **Position Segregation:** Counted employees across positions (`value_counts()`), plotted a bar chart (`plt.bar`).
3. **Age Group:** Grouped ages into brackets, found the top group (`.idxmax()`), plotted a bar chart (`plt.bar`).
4. **Salary Expenditure:** Summed salaries by team and by position (`groupby().sum()`), found the highest (`.idxmax()`), plotted bar charts (`plt.bar`).
5. **Age vs. Salary:** Checked correlation (`.corr()`) and plotted a scatter plot (`plt.scatter`).

## Key Insights
Most teams have around **14 to 19** employees (often **15**), employees are spread across positions, and most fall into younger-to-middle age groups. Salary totals vary across teams and positions, and age alone shows only a weak link to salary.

## How to Run in Colab
1. Open the notebook in **Google Colab** and upload `ABC Company Dataset.csv` in the left **Files** panel.
2. Click **Runtime → Restart and run all** to run every cell cleanly from top to bottom.
