# Maven Northwind Challenge - Data Cleaning

This repository contains the data cleaning and preparation steps for the Maven Northwind Challenge, an analysis project focused on sales and order data for the fictitious gourmet food supplier, Northwind Traders.

## Project Description

The Maven Northwind Challenge is a project involving multiple tables of data, including information on customers, products, orders, shippers, and employees. The goal of this stage of the project was to clean and prepare the data for further analysis in Tableau. 

## Data Preparation Steps

1. **Loading the data**: The data was loaded from multiple CSV files, each representing a table from the Northwind database.

2. **Merging the data**: The tables were merged using Python's Pandas library. The merged dataframe provided a complete view of the order data, along with associated customer, product, and shipping information.

3. **Cleaning the data**: The merged data was then cleaned, with steps including handling missing values, dropping unnecessary columns, and renaming columns for clarity.

## Libraries Used 

* Pandas: Used for loading, merging, and cleaning the data.

## Results

The result of this data cleaning and preparation process is a single CSV file ready for analysis in Tableau. The cleaned data includes only relevant columns, with all missing values appropriately handled.

## Next Steps

With the data cleaned, the next stage of the project involves analyzing the data in Tableau to answer questions such as:
- Are there any noticeable sales trends over time?
- Which are the best and worst selling products?
- Can we identify any key customers?
- Are shipping costs consistent across providers?

Stay tuned for the Tableau analysis!

## Check out the full project

You can view the full project including the final Tableau dashboards at my [Tableau Public Profile](https://public.tableau.com/app/profile/suleyman.yahaya/viz/NavigatingtheTradeWindsANorthwindAnalysis/TradeWindsTrackerASalesPerformanceBoard).
