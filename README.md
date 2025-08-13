# 📊 Data Analysis

## 📌 Objective
The goal of this task is to analyze sales data from a CSV file using Pandas for data processing and Matplotlib for visualization.

## 🛠 Tools & Libraries
- Python (3.x)
- Pandas – for loading and manipulating data
- Matplotlib – for creating charts
- Jupyter Notebook / Google Colab – for running the analysis interactively

## 📂 Dataset
File : `sales_data_sample.csv`  
The dataset includes :
- Order details (order number, quantity, price, sales)
- Date and time of orders
- Customer location (city, country)
- Product line and deal size

## 📋 Steps Performed
1. Importing Libraries – Loaded Pandas and Matplotlib.
2. Loading the Dataset – Used Pandas `read_csv()` to import the file.
3. Data Grouping – Applied `groupby()` and `sum()` to calculate :
   - Total sales per year
   - Total sales per month
   - Total sales per country
4. Visualization – Created bar charts to display :
   - Yearly sales trends
   - Monthly sales patterns
   - Sales distribution by country

## 📊 Analysis Insights
- **Yearly Trends:** Shows whether sales are increasing or decreasing over the years.
- **Seasonality:** Highlights which months perform better in terms of sales.
- **Geographic Performance:** Reveals which countries generate the most revenue.

## ▶ How to Run
1. Install the required libraries: Pandas and Matplotlib.
2. Place the CSV file in your working directory.
3. Open the notebook in Jupyter or Colab.
4. Run the cells in order to generate the charts.
