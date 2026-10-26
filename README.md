[README_data_analyst_two.md](https://github.com/user-attachments/files/33962432/README_data_analyst_two.md)
# data_anlyst-two-
THIS IS PROJECT OF DATA ANLYST .
# Sales and Business Performance Analysis

This project explores sample business data to visualize revenue, costs, sales volume, and performance across regions, product categories, and quarters.

## Project Overview

The notebook creates a dataset of 100,000 rows using NumPy and Pandas, then uses charts to examine regional distribution, category mix, revenue, shipping costs, and relationships among selected business metrics.

## Dataset

The data is generated inside the notebook with a fixed random seed (`42`), so a separate CSV file is not required. It contains these columns:

- `Region`
- `Category`
- `Quarter`
- `Total_Revenue`
- `Shipping_Cost`
- `Ad_Spend`
- `Net_Profit`
- `Units_Sold`
- `Operational_Cost`
- `Customer_Count`

The values are randomly generated for demonstration and should not be treated as real company results.

## Analysis Included

- Number of records by region
- Distribution of product categories
- Total revenue by region
- Quarter distribution
- Revenue distribution and boxplot
- Total revenue by category
- Shipping-cost distribution
- Correlation heatmap for selected numeric measures
- Pairplot of advertising spend, net profit, and units sold by region

## Libraries Used

- **NumPy** — generating sample data and numerical operations
- **Pandas** — creating and grouping tabular data
- **Matplotlib** — charts and plots
- **Seaborn** — statistical visualizations

## Installation

Install the required libraries:

```bash
python -m pip install numpy pandas matplotlib seaborn notebook
```

## How to Run

1. Download or clone the repository.
2. Install the required libraries.
3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the notebook and run the cells in order.

## Purpose

This project demonstrates basic business-data analysis and visualization techniques that can help communicate regional and category-level patterns.

## Note

Because the notebook generates random sample data, the results are for practice and demonstration only. They should not be used to make real business decisions.
