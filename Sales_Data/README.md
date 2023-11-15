# Python

# Python Project: Sales Data Analysis

This repository contains Python scripts for conducting an Exploratory Data Analysis (EDA) on a sales dataset.

## Project Description

The goal of this project is to answer the following questions:

1. **What was the best month for sales? How much was earned that month?**
2. **What city sold the most product?**
3. **What time should we display advertisements to maximize the likelihood of customer’s buying product?**
4. **What products are most often sold together?**
5. **What product sold the most? Why do you think it sold the most?**

## Files / Folder
- `Sales_Data/`: This folder contains the monthly sales data in CSV format.
- `sales_data.csv`: This is the main dataset used for the analysis (the concat of the file in the folder `Sales_Data/`). It contains sales data including date, product, quantity, price, and location of sale.
- `eda.ipynb`: This Jupyter notebook contains the Python code used for the EDA. It includes data cleaning, data visualization, and data analysis sections.

## Usage

To run the EDA script, you need to have Jupyter Notebook installed. You can then clone this repository and open `eda.ipynb` in Jupyter Notebook.

## Insights

Here are some insights from the data:

- **Best Month for Sales and Earnings**: October and December were the best months for sales, with earnings of '3M7' and '4M6,' respectively. These months consistently outperformed January.
- **City with Most Product Sales**: 'San Francisco (CA)' stands out as the city with the highest quantity of products sold, while 'Portland (ME)' had the lowest quantity of products sold.
- **Optimal Advertisement Times**: To maximize the likelihood of customer purchases, consider displaying advertisements around 11 AM, 12 PM, and 7 PM. These times correspond to peak sales hours when customers are more likely to buy products.
- **Frequently Sold Together Products**: Customers often purchase a combination of a phone, charging cable, and headphones. This indicates that when customers buy a phone, they tend to buy these accessories for a seamless experience.
- **Best-Selling Product**: The product that sold the most is the AAA Batteries (4-pack) with 31,012 quantity ordered. This can be attributed to its affordability, necessity, and convenience for consumers.
- **Analysis of Customer Purchasing Habits by Day of the Week**: Customer purchasing habits show relatively small differences throughout the week. This suggests consistent sales across weekdays and weekends.
