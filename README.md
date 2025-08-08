# Sales Data Analysis using Pandas

This project demonstrates how to analyze a simple sales dataset using **Python**, **Pandas**, and **Matplotlib** in **Jupyter Notebook or Google Colab**. It provides insights like revenue by product and region, along with visualizations.

## Objective

To perform basic data analysis on a CSV file containing sales data and visualize the insights using charts.

## Tools & Libraries

- Python 3.x
- Pandas
- Matplotlib
- Jupyter Notebook or Google Colab

## Project Structure

SalesDataAnalysis/
├── salesdata.csv # Sample sales dataset
└── salesanalysis.ipynb # Jupyter/Colab notebook with analysis

## Dataset Overview

`salesdata.csv` contains the following columns:

| Column   | Description               |
|----------|---------------------------|
| Date     | Date of the sale          |
| Product  | Product name              |
| Region   | Sales region              |
| Quantity | Number of items sold      |
| Price    | Price per unit            |

## Steps Covered in the Notebook

1. Load and preview the dataset
2. Calculate revenue (Quantity × Price)
3. Analyze:
   - Total revenue
   - Revenue by product
   - Revenue by region
4. Visualize insights using:
   - Bar chart for product sales
   - Pie chart for region sales

## Sample Output

- **Total Revenue**: `$X.XX`
- **Top Product**: Notebook
- **Top Region**: North

### Product-wise Sales Chart

![Bar Chart]

### Region-wise Sales Pie Chart

![Pie Chart]

> *You can generate these charts by running the notebook.*

## How to Run

### Using Jupyter Notebook

```bash
pip install pandas matplotlib
jupyter notebook
```


