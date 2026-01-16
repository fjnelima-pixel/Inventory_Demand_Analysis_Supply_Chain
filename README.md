# Inventory & Demand Planning Analysis for Supply Chain Optimization

## Overview
This project demonstrates an end-to-end inventory and demand planning analysis for a mid-sized company. 
It shows how data-driven insights can help optimize inventory, reduce stockouts and improve supplier performance. 
The project is implemented in Python using Pandas, NumPy and Matplotlib in Google Colab.


## Business Problem
A company wants to better manage its inventory and meet customer demand efficiently. 
Key challenges include:

- Stockouts of fast-moving products  
- Excess inventory of slow-moving items  
- Supplier delays affecting fulfillment  
- Lack of demand forecasting for planning  

**Objective:** 
Use historical order and sales data to analyze demand, assess inventory performance, forecast future deman, and provide actionable recommendations.


## Dataset
The dataset contains historical order data including:

| Column | Description |
|--------|-------------|
| `Order_Date` | Shipping date of the order |
| `Product Name` | Name of the product |
| `Category Name` | Product category |
| `Sales` | Sales per customer |
| `Lead_Time` | Days taken for shipping |
| `Late_Risk` | Risk of late delivery |

_Source: Kaggle Supply Chain Dataset (DataCoSupplyChainDataset.csv)_


## Key Analyses
1. **Data Cleaning & Preparation**  
   - Converted dates to datetime  
   - Handled missing values  
   - Selected relevant columns  

2. **Exploratory Data Analysis (EDA)**  
   - Daily demand trends  
   - Total sales per product and category  
   - Lead time analysis  
   - Late delivery risk assessment  

3. **Inventory KPIs**  
   - Fast vs slow moving products  
   - Stockout risk proxy using lead time and sales  
   - Supplier performance indicators  

4. **Demand Forecasting**  
   - 7-day moving average forecasts for total and top products  
   - Trend analysis to identify seasonal patterns  

## Insights & Recommendations
- Maintain higher safety stock for fast-moving SKUs  
- Reorder products with high lead times or late delivery risk earlier  
- Reduce inventory for slow-moving items to free working capital  
- Use moving average forecasts for short-term demand planning  
- Monitor supplier performance and prioritize high-risk items  


## Author  
Faith N. Weyombo -Supply Chain & Data Analyst 
