# Superstore Sales Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Sample Superstore dataset. The purpose is to study sales, profit, discounts, customer segments, regions, product categories, returns, and unusual order patterns.

## Objectives

* Load and understand the Superstore dataset.
* Perform data cleaning and check missing values.
* Calculate descriptive statistics.
* Identify sales and profit trends.
* Analyse relationships between sales, discount, and profit.
* Compare categories, sub-categories, regions, and customer segments.
* Detect outliers in sales and profit.
* Provide business insights and recommendations.

## Dataset

The dataset used in this project is:

`Sample - Superstore dataset.xlsx`

It contains three sheets:

* **Orders:** Customer, product, sales, quantity, discount, and profit information.
* **Returns:** Details of returned orders.
* **People:** Regional manager information.

The Orders sheet contains 9,994 records and 21 columns.

## Tools and Libraries

This project was created using Python in Jupyter Notebook.

Libraries used:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Openpyxl

## Project Structure

```text
Task-2_Exploratory_Data_Analysis(EDA)/
│
├── data/
│   └── Sample - Superstore dataset.xlsx
│
├── Superstore_EDA.ipynb
├── README.md
└── requirements.txt
```

## Analysis Performed

1. Data loading and inspection
2. Data quality check
3. Missing value analysis
4. Descriptive statistics
5. Sales and profit analysis
6. Category and sub-category analysis
7. Region and customer-segment analysis
8. Monthly sales and profit trend analysis
9. Discount versus profit analysis
10. Return analysis
11. Outlier detection using the IQR method
12. Business findings and recommendations

## Key Business Questions

* Which category and sub-category generate the most sales and profit?
* Which sub-categories are making losses?
* Which region and customer segment perform best?
* How do sales and profit change over time?
* Does discount affect profit?
* How many orders were returned?
* Which sales and profit values are unusual outliers?

## How to Run the Project

1. Install Python and Jupyter Notebook.
2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `Superstore_EDA.ipynb`.
5. Run all cells using **Run → Run All Cells**.

## Conclusion

This project uses EDA to identify profitable areas, loss-making products, discount-related risks, return patterns, and unusual order values. The findings can help a retail business make better decisions about pricing, discounts, product categories, and regional sales strategy.
