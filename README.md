# Analysis-of-Car-Sales-Data-Using-Big-Data-Infrastructure-and-Analytics-Techniques

Project Overview

This project is based on the Car Sales Data dataset sourced from Kaggle (https://www.kaggle.com/datasets/suraj520/car-sales-data?resource=download). The dataset contains detailed records of car sales, including information about vehicles, pricing, and commission. 

Dataset Summary

Number of rows: 2,500,000 records.
Number of columns: 9 main attributes describing each sale.

Columns: 

1. Date (The date when the car was sold)
2. Salesperson (Name of the salesperson who closed the sale)
3. Customer Name (Name of the customer who bought the car)
4. Car Make (Brand/manufacturer of the vehicle)
5. Car Model (Specific model of the vehicle)
6. Car Year (Year of the vehicle model)
7. Sale Price (Price at which the car was sold)
8. Commission Rate (Commission percentage for the salesperson)
9. Commission Earned (Absolute commission amount earned on the sale)

Problem Domain: 

Analysis of car sales patterns and factors influencing the formation of sales prices based on a historical car sales dataset

Research Questions

1. What are the sales patterns of cars (annual, quarterly, monthly and daily)?
2. Are there significant differences in car sale prices depending on the make, model and year of manufacture?
3. Which car makes and models achieve the highest sales volume and the highest average sale price?
4. What is the relationship between a car's age and its sale price?
5. How does the commission rate affect earned commission and do higher commission rates lead to higher total revenue?
6. Is it possible to predict car sales prices with satisfactory accuracy using a SparkML model based on the available features?

Project Workflow

1. Data Cleaning: detection and handling of missing values, removal of duplicates and inconsistent entries, standardization of data formats for dates, strings, and numeric fields, extracting year, month, quarter and day of the week from date fields (feature engineering)
2. Database Integration: importing the processed dataset into MongoDB to enable advanced query-based analysis and aggregation.
3. Query-Based Analysis: exploring relationship between variables, computing summary statistics, and answer research questions through queries using MongoDB aggregations.
4. Visualization: producing visual interpretatios using Matplotlib and Seaborn.





