# SP-
Project on Sales Performance Analysis




Title: Leveraging the "Superstore Sales" Dataset for In-Depth Data Analysis and Insights

#Abstract:

The "Superstore Sales" dataset is a valuable resource offering a wide array of data that can provide significant insights into various aspects of business operations, such as sales, customer behavior, and product performance. This report explores the dataset's richness and versatility, detailing its potential applications in data analysis, research, and business strategy.

#Introduction:

The "Superstore Sales" dataset is a comprehensive collection of data encompassing sales transactions, customer demographics, and product details. This dataset provides a wealth of opportunities for data analysts, researchers, and businesses to uncover actionable insights that can drive success in pricing strategies, supply chain management, and customer engagement.

#Dataset Overview:

The dataset includes information from diverse regions and segments, allowing for the exploration of trends, patterns, and correlations in sales and customer preferences. It contains the following key components:

1.Sales Transactions

2.Customer Demographics

3.Product Performance Metrics

4.Geographic Information

5.Discounts and Promotions

#Resources

Dataset used was sourced from kaggle, Superstoresales Dataset(2011-2014). It is organised as a long data which contains 18 columns and 9995 rows.

Columns include:

Order Date

Ship Date

Ship Mode

Customer ID

Customer Name

Segment

City

State

Postal code

Region

Product ID

Category

Sub-Category

Product Name

Sales

Quantity

Discount

Profit

Analysis and Visualization was done using Excel and PowerBI.

#Data Cleaning

After downloading the data from Kaggle, I needed to clean the data to perform an exploratory data analysis. First, i checked for missing data and discovered none. 
Some columns like Row ID, Segment and Postal code were deleted.

#Exploratory Data Analysis

After filtering out the not-needed columns, the table was moved to PowerBI where data modelling was carried out by analyzing the relationships between various columns on the table. A 6-page report was carried :

#Sales Performance Analysis:

Here, high-demand/most profitable products were identified, the effectiveness of different shipping mode was assessed and sales trend over months, quarters and years was analyzed. Insights derived from this analysis can guide decision-making and strategy formulation.

#Customer Behavior Analysis:

The dataset enables the segmentation of customers based on their demographics, buying patterns, and purchasing history. The top 10 customers were analyzed based on sales and profit. I realized that the customer with the highest purchase incurred losses to the company and this was due to the discounts given to the customer. This information can be leveraged to tailor marketing strategies and enhance customer engagement.

#Product Performance Evaluation:

The dataset provides metrics for evaluating product performance. I identified the top-selling and under-performing products through sales and profit, informing inventory management and product development decisions.

#Pricing Strategy Optimization:

I analyzed the impact of discounts and promotions on sales and profitability. This would help the business refine their pricing strategies to maximize revenue.

#Geospatial Insights:

Geographical analysis could not be carried out through the use of map and this was due to data type used for this column when creating this table. I visualized the data using bar chart showing the top-selling and under-performing region and also the top 10 selling and profitable cities. This can be useful for regional expansion or optimization of distribution networks.

#Data Visualization

![SALES PERFORMANCE ANALYSIS DASHBOARD](https://github.com/Nini-Visualization/SP-/assets/148988525/cfd1fe8c-e5af-4707-a1b2-7ff9b12a6c67)
![CUSTOMER BEHAVIOUR ANALYSI![GEOSPATIAL INSIGHTS](https://github.com/Nini-Visualization/SP-/assets/148988525/93449af1-6660-4961-a8de-64004e3abf5a)
![PRICING STRATEGY OPTIMZATION](https://github.com/Nini-Visualization/SP-/assets/148988525/0b5fb30e-30d4-4b9c-b2a4-d557f3540c7b)
![GEOSPATIAL INSIGHTS](https://github.com/Nini-Visualization/SP-/assets/148988525/3a75306f-3616-4794-b815-8a678d263cea)

#Insights

-Discount promotion did not influence purchases. Profits was made more from zero discount sales.

-New York city ranked the highest selling/most profitable city by the company. Philadelphia ranked the 5th highest selling city but the least profitable city among the top 10 cities.

-Sean Miller ranked the highest buying customer but incurred losses for the company through the use of huge discounts provided by the company.

-The copiers products ranked the most profitable product for the company.

-The superstore sales experienced a linear growth between 2011-2014. In 2014, they made the highest sales and profit and had the highest customer count.
