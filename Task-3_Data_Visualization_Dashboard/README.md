# Superstore Data Visualization Dashboard

## Project Overview

This project analyses the Sample Superstore dataset and presents business insights through data visualizations.

The project includes:

- A Python Jupyter Notebook for data visualization.
- An interactive Power BI dashboard for the bonus task.

The visualizations help understand sales, profit, product categories, regions, customer segments, time-based trends, and sales distribution.

## Objectives

- Convert raw Superstore data into meaningful visualizations.
- Create bar charts, line charts, donut charts, histograms, scatter plots, and heatmaps.
- Analyse sales, profit, categories, regions, and customer segments.
- Present data through a professional interactive Power BI dashboard.
- Use filters to explore the data dynamically.

## Dataset

Dataset used:

```text
Sample - Superstore dataset.xlsx
```

The dataset contains three sheets:

- **Orders:** Order, customer, product, sales, quantity, discount, and profit details.
- **Returns:** Returned order details.
- **People:** Regional manager details.

## Tools Used

### Python Visualization

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Openpyxl

### Interactive Dashboard

- Microsoft Power BI Desktop
- Microsoft Excel

## Jupyter Notebook Visualizations

The Python notebook includes:

1. KPI Summary
   - Total Sales
   - Total Profit
   - Total Orders
   - Total Customers

2. Bar Chart
   - Total Sales by Category

3. Line Chart
   - Monthly Sales Trend

4. Pie Chart
   - Sales Distribution by Region

5. Histogram
   - Distribution of Sales

6. Scatter Plot
   - Relationship Between Sales and Profit

7. Heatmap
   - Sales by Region and Customer Segment

## Power BI Dashboard Visualizations

The interactive Power BI dashboard includes:

1. KPI Cards
   - Total Sales
   - Total Profit
   - Total Orders
   - Total Customers

2. Sales by Category
   - Column chart

3. Monthly Sales Trend
   - Line chart

4. Sales by Region
   - Donut chart

5. Profit by Sub-Category
   - Horizontal bar chart

6. Sales vs Profit
   - Scatter chart

7. Sales Distribution
   - Histogram

## Interactive Filters

The Power BI dashboard includes slicers for:

- Region
- Category
- Segment

These filters update all KPI cards and charts automatically.

## Dashboard Design

The Power BI dashboard uses:

- A clean light background.
- Consistent dark-blue headings.
- Color-coded KPI cards.
- White chart containers.
- Light-grey borders.
- Rounded corners for cards, charts, and filters.
- Clear chart titles and labels.

## Project Structure

```text
Data_Visualization_Dashboard/
│
├── data/
│   └── Sample - Superstore dataset.xlsx
│
├── Superstore_Visualization_Dashboard.ipynb
├── Superstore_PowerBI_Dashboard.pbix
├── dashboard_screenshot.png
├── README.md
└── requirements.txt
```

## How to Run the Python Notebook

1. Install the required libraries:

```bash
pip install -r requirements.txt
```

2. Open Jupyter Notebook:

```bash
jupyter notebook
```

3. Open:

```text
Superstore_Visualization_Dashboard.ipynb
```

4. Run all cells.

## How to Open the Power BI Dashboard

1. Install Microsoft Power BI Desktop.
2. Open:

```text
Superstore_PowerBI_Dashboard.pbix
```

3. If Power BI requests the data source, select:

```text
data/Sample - Superstore dataset.xlsx
```

4. Use the Region, Category, and Segment slicers to interact with the dashboard.

## Key Insights

- Technology is the highest-selling product category.
- Sales change over time, as shown in the monthly sales trend.
- Sales contribution differs across regions.
- Profit differs across product sub-categories.
- Sales and profit do not always increase together.
- Most orders fall into lower sales ranges, while a few are high-value orders.
- Interactive filters make it easy to compare business performance across regions, categories, and customer segments.

## Conclusion

This project uses Python visualizations and an interactive Power BI dashboard to make Superstore business data easy to understand. It supports decisions related to product categories, regional performance, customer segments, sales trends, and profitability.
```