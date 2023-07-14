# SuperStoreOrders-Data-Analytics-using-python

# INTRODUCTION


I took part in a 10days Data Analytics Challenge on a Super Store Orders Database of over 50,000 data to find insights, trends, patterns and come up with business decisions.
I will be using python and Tableau for this project.
let me start by defining the project objectives

1. Which product has the highest number of sales and in which country and region?

2. Which product has the highest number of customer demands, in what country and region?

3. Which product or products produced the highest profit?
4. How does the shipping cost and method affect the sales of products

Join me as I take you through the process and allow me show you how business decisions are made with Data Analytics.

The dataset contains the following key variables;
order_id, order_date, ship_date, ship_mode, customer_name, segment, state, country, market, region, product_id, category,  sub_category,
product_name, sales, quantity, discount, profit, shipping_cost, order_priority, year.

The dataset
[SuperStoreOrders.csv](https://github.com/Hykze1/SuperStoreOrders-Data-Analytics-using-python/files/12026113/SuperStoreOrders.csv)


Firstly, Data Cleaning is a very important part of Data Analysis because real-world datasets frequently include a variety of problems,including outliers, inaccurate or inconsistent data entries, duplicate records, missing values, inconsistent formatting, and inconsistent formatting. These problems may occur as a result of human error during data entry, computer errors,
data integration from several sources, or other circumstances.

# DATA CLEANING

HERE ARE SOME OF THE PRIMARY OBJECTIVES WE CARRY OUT DATA CLEANING

  1.REMOVING IRRELEVANT OR REDUNDANT DATA: This entails removing variables or columns that do not help to the analysis,
have no value or not consistent with the project objectives.

2. HANDLING MISSING DATA: Missing data can be problematic and can change analytical results.
Depending on the unique situation and the objectives, data cleaning procedures are used to resolve missing values by either
imputing them (estimating the missing values based on other data points) or eliminating the records with missing values.
3. CORRECTING INCONSISTENCIES: To guarantee data integrity and accuracy, inconsistent data entries such as misspellings, multiple
representations of the same value (e.g., "USA," "United States"), or contradicting information must be handled. This could entail
standardizing formats, merging comparable categories, or resolving conflicting values via manual or automated processes.

Next we do DESCRIPTIVE (STATISTICAL) ANALYSIS on the dataset so as to derive more insight from the data.
This is an integral part of EXPLORATORY DATA ANALYSIS (EDA) and a key aspect to help us derive deeper meaning from our data

filtering and spliting the data into different years available in the dataset: 2011, 2012, 2013, 2014 and then from 2011 to 2014.

And many more analysis were done which include Important KPI

# KPI OUTPUT

DISCOUNT VS SALES, QTY AND PROFIT

![image](https://github.com/Hykze1/SuperStoreOrders-Data-Analytics-using-python/assets/100960483/1714dd15-3eef-4fe0-b20b-063c1c544332)

DESCRIPTIVE ANALYSIS OF SALES,QTY AND PROFIT IN ORDER OF PRIORITIES

![image](https://github.com/Hykze1/SuperStoreOrders-Data-Analytics-using-python/assets/100960483/50c676eb-48d8-42f7-8b4d-5ef6c4fb8253)

DESCRIPTIVE ANALYSIS
![image](https://github.com/Hykze1/SuperStoreOrders-Data-Analytics-using-python/assets/100960483/cf0b56ee-cc05-49b1-bac9-31fe6a9c75f3)

SHIPPING VS PRODUCT,SALES AND PROFIT
[Shipping Cost VS product,Sales and Profit.xlsx](https://github.com/Hykze1/SuperStoreOrders-Data-Analytics-using-python/files/12026612/Shipping.Cost.VS.product.Sales.and.Profit.xlsx)

# Tableau visualization

![tableaux ike 2](https://github.com/Hykze1/SuperStoreOrders-Data-Analytics-using-python/assets/100960483/8b3bece2-7a22-4501-ba3e-cd469ac4d3b9)

# KPI ANALYSIS AND BUSINESS ADVICE

KPI 1:
The chat shows that the store is facing lower profits due to high shipping costs, here are some advice and strategies that can be considered:

1. Negotiate Shipping Rates: Engage in negotiations with shipping carriers to secure better rates based on the company's shipping volume. Consolidating shipments, using specific carriers for certain routes, or exploring long-term contracts may help reduce costs.

2. Optimize Packaging: Analyze the packaging used for products to ensure it is efficient and minimizes wasted space. Choosing the right packaging size and weight can potentially lower shipping costs, as carriers often consider both factors in their pricing structure.

3. Implement Shipping Cost Analysis: Regularly review and analyze shipping costs for different products, destinations, and shipping methods. Identify any discrepancies or areas of high cost and develop strategies to address them.

In conclusion:

It's important to analyze the specific challenges and dynamics of the company's shipping costs to tailor the advice accordingly. A comprehensive review of shipping processes, carrier contracts, and customer expectations can provide insights for optimizing costs while maintaining customer satisfaction and profitability.

KPI 2:The chat shows  has identified a particular region with the highest sale of office supplies, here are some advice and strategies to consider:

1. Market Segmentation: Analyze the demographics and characteristics of the customers in the region. Identify any specific segments or industries that contribute significantly to the office supplies sales. This information can help tailor marketing and sales strategies to target those segments more effectively.

2. Increase Local Marketing Efforts: Allocate a larger portion of the marketing budget to target the specific region. Develop localized advertising campaigns, sponsor local events, and collaborate with regional influencers or businesses to increase brand visibility and capture a larger market share.

3. Competitive Analysis: Conduct a thorough analysis of the competition in the region. Identify their strengths, weaknesses, pricing strategies, and unique selling points. Differentiate the company's offerings by highlighting key benefits, superior customer service, or exclusive product lines.

In conclusion:
By focusing on the region with the highest sales of office supplies and implementing tailored strategies, the company can further capitalize on the existing market demand and drive business growth in that specific area.

KPI 3: The chat shows that the store is experiencing higher sales and quantity but lower or fluctuating profits due to offering higher discounts, here are some advice and strategies to consider:

1. Review Pricing Strategy: Assess the current pricing structure and evaluate whether it aligns with the company's profit goals. Analyze the impact of discounts on profit margins and determine if adjustments need to be made to ensure profitability while still remaining competitive.

2. Analyze Cost Structure: Conduct a thorough analysis of the company's cost structure to identify areas where costs can be optimized. Look for opportunities to reduce production costs, streamline operations, negotiate better supplier contracts, or improve inventory management to offset the impact of discounts on profits.

3. Cost of Goods Sold (COGS) Optimization: Evaluate the cost of goods sold for the products offered. Explore opportunities to optimize sourcing, production processes, and supply chain management to reduce costs without compromising quality. This can help increase profitability even with discounts.

4. Targeted Discounting: Instead of offering blanket discounts, consider implementing targeted discounting strategies. Identify specific customer segments, products, or purchasing behaviors that would benefit from discounts and tailor the offers accordingly. This helps prevent unnecessary discounts that erode profits without generating substantial additional sales.

5. Analyze Sales and Profit Data: Regularly review and analyze sales and profit data to identify trends, patterns, and areas of improvement. Identify the specific products or customer segments that contribute most to profits and focus efforts on maximizing profitability in those areas.

In conclusion:
Balancing sales growth and profitability requires a strategic approach to discounts. By implementing targeted discounts, optimizing costs, and focusing on long-term customer relationships, the company can maximize profitability while still benefiting from increased sales volume.
