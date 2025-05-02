# Stellar Group Performance Analysis 

[Introduction](#Introduction)

[Objective](Objective)

[Story of Data](#StoryofData)

[Data Splitting and Preprocessing](#DataSplittingandPreprocessing)

[Pre-Analysis](#Pre-Analysi)

[In-Analysis](#In-Analysis)

[Post-Analysis and Insights](#Post-AnalysisandInsights)

[Data Visualizations & Charts](#DataVisualizations&Charts)

[Recommendations and Observations](#RecommendationsandObservations)

[Conclusion](#Conclusion)

[References & Appendices](#References&Appendices)

## Introduction
This project analyzes the given sales dataset to uncover valuable insights that can support data-driven decision-making. The analysis processes, cleans, and interprets the data to identify key trends, correlations, and actionable recommendations. By applying structured methodologies, the project enhances the understanding of business performance, customer purchasing behavior, and areas for improvement.
In today’s competitive business environment, data is a critical asset for making informed decisions. The dataset under analysis contains vital business metrics such as sales figures, customer details, and transaction records. This data provides an opportunity to:
•	Understand customer purchasing behavior.

•	Detect patterns in sales performance.

•	Identify factors affecting business growth.

By organizing and analyzing this data, businesses can gain clarity on their operations and strategize effectively.

## Objective
The goal of this analysis is to evaluate sales performance across various dimensions to support data-driven decision-making. 

•	Sales Trend Report helps identify patterns, seasonal fluctuations, and overall sales growth over time. 

•	The Top 10 Customers report highlights the most valuable clients, enabling targeted marketing and retention strategies. 

•	Sales by Salespersons assesses the contributions of individual sales reps, aiding in performance evaluation and incentive planning.

•	Sales by Region provides insights into geographical sales distribution, helping businesses optimize resources and marketing efforts. 

•	Transaction by Amount categorizes transactions based on their monetary value, offering visibility into revenue-generating activities. 

•	Top 6 Shipping Cities by Revenue and Top 5 Cities by Revenue reports pinpoint high-revenue locations, guiding logistical improvements and business expansion strategies. 

Overall, this analysis provides actionable insights to enhance sales performance and 

### Problem Being Addressed
Businesses often struggle with making data-driven decisions due to unstructured or incomplete information. This analysis seeks to address challenges such as:

•	Understanding the factors influencing sales performance.

•	Identifying gaps or inefficiencies in customer acquisition strategies.

•	Providing recommendations based on data-backed insights.

### Key Datasets and Methodologies
•	Datasets Used: The dataset is a Grocery Store dataset which includes transaction records, customer details, product-related data, revenue, region, cities, and salespersons, etc.

•	Methods Used: The analysis utilizes Microsoft Excel tools, such as:

  * Pivot Tables for data summarization.

  * Data Cleaning Techniques such as removing duplicates and blank spaces, and empty rows, to ensure data quality.

  * Visualizations (charts and graphs) to illustrate trends.
## Story of Data

### Data Source 
The dataset originates from internal company sales records, capturing transactions, product details, customer demographics, and revenue figures.
Data Collection Process: Sales data was recorded from transactional databases, capturing order details, customer information, region, sale persons, shipping information, and revenue figures for analysis.

### Data Structure

•	Each row represents an individual sales transaction.

•	Columns include order ID, product name, revenue values, shipper name, ship city, and customer demographic details etc.

### Important Features and Their Significance

•	Revenue: The core metric used to evaluate sales performance and profitability.

•	Product Names: Helps identify top-performing products and trends in customer preferences.

•	Revenue Values: Essential for assessing financial impact and contribution per product or region.

•	Shipper Name & Ship City: Provides insights into logistical performance and regional sales distribution.

•	Customer Demographics: Useful for segmenting customers based on purchasing behavior and targeting marketing efforts accordingly.

### Data Limitations or Biases:

•	Some missing records for ship city and shipper names.

•	Lack of complete demographic data may limit segmentation analysis. Some missing records for ship city and shipper names.

•	Data may not capture recent market trends, as it is based on historical transactions.

•	Potential data entry errors affecting accuracy.

•	Limited product categories may restrict broader insights into the overall market.

•	Lack of detailed customer behavior metrics, such as purchase frequency and customer lifetime value.

## Data Splitting and Preprocessing

### Data Cleaning

•	Removed duplicates and ensured consistent formatting.

•	Addressed missing values where possible.

•	Removed unnecessary spaces between words using excel function “Trim”

### Handling Missing Values
Some of the column had missing valued, which can be handled by using;

•	Find & Replace (Ctrl + H): Replace blanks with zero or a placeholder. 

•	Go To Special (F5 → Special → Blanks): Select all blank cells and enter a common replacement value 

### Data Transformations

•	Aggregated sales data by month, region, category, sale-person, city, ship-city, and customer

### Data Splitting

We Separated the dataset into independent and dependent values 

Independent Values

•	Customer Name

•	Sales person

•	Country/Region

•	Ship Name

•	Region

•	Ship Country

•	Payment Type

•	Product Name 

•	Category, etc.

 Dependent Values
 
•	Quantity

•	Revenue

•	Shipping Fee

•	Unit Price 

### Industry Context

The dataset belongs to the retail/e-commerce industry, where businesses sell products directly to consumers through physical stores or online platforms. This industry heavily relies on data analysis for sales forecasting, inventory management, and customer behavior insights.

### Relevance to the Analysis

•	Sales Forecasting: Understanding seasonal trends helps predict demand and optimize stock levels.

•	Inventory Management: Identifying top-performing products ensures efficient supply chain operations.

•	Customer Segmentation: Analyzing demographics allows for targeted marketing strategies.

•	Regional Performance Evaluation: Comparing revenue across different locations supports strategic expansion and market penetration efforts.

### Stakeholders
Senior management, sales teams, and marketing departments.

### Value to the Industry
This sales analysis provides critical insights that drive strategic decision-making in the retail/e-commerce industry, leading to improved business efficiency and profitability. The key areas of impact include:

1.	Pricing Optimization:

•	By analyzing revenue trends and regional sales performance, businesses can identify optimal pricing strategies to maximize profitability.
•	Seasonal sales data helps in adjusting prices dynamically to match demand fluctuations.

3.	Identification of Best-Selling Products:
•	The analysis pinpoints top-selling products, allowing businesses to focus on high-performing categories and allocate resources effectively.
•	Understanding which products generate the most revenue aids in demand forecasting and inventory management.
4.	Marketing Strategy Refinement:
•	Customer demographic insights help in segmenting the market and tailoring promotional campaigns.
•	By identifying the most profitable regions, businesses can optimize advertising spend and enhance customer engagement.
5.	Supply Chain and Logistics Optimization:
•	Evaluating sales by region and shipper performance helps streamline logistics, reducing costs and improving delivery efficiency.
•	Insights into shipping cities and revenue distribution assist in selecting better distribution centers and improving customer satisfaction.
6.	Strategic Business Expansion:
•	Regions with consistent high sales can be targeted for new store openings or increased marketing investments.
•	Understanding underperforming areas allows businesses to explore new strategies to improve penetration and sales.
By leveraging these insights, companies can increase revenue, reduce operational inefficiencies, and improve customer satisfaction, ultimately gaining a competitive advantage in the industry.
5.	Pre-Analysis 
Identify Key Trends
•	Sales show fluctuations across months, indicating strong seasonality, likely influenced by external factors such as holidays, promotions, or economic conditions.
•	Certain regions consistently outperform others in revenue generation, suggesting geographical variations in consumer demand and purchasing power.
•	Repeat purchases from top customers indicate a loyalty pattern, which could be leveraged for personalized marketing strategies.
•	Sales representatives contribute differently to total revenue, highlighting possible performance gaps that may require further investigation.
Potential Correlations
•	High sales concentration in specific product categories such as beverages suggests targeted consumer preferences, indicating that some product lines perform better than others across different regions.
•	A strong relationship between ship cities and revenue generation suggests that logistical efficiency and delivery times may influence purchasing decisions.
•	Certain sales reps are responsible for significantly higher sales such as Nancy freehafer, implying that sales performance may be impacted by factors such as customer relationships, experience, or region-specific demand.
•	Higher transaction amounts appear linked to specific customers, possibly indicating bulk buyers or corporate clients who contribute significantly to revenue.
Initial Insights:
•	Beverages and sauces are top-selling categories, suggesting a strong consumer preference for consumables within the product mix.
•	The North and East regions contribute significantly to revenue, indicating these are key markets that should be prioritized for marketing and supply chain optimization.
•	Top 10 customers account for a significant portion of total sales, reinforcing the importance of customer retention strategies to maximize lifetime value.
•	Shipping efficiency and preferred shippers may influence customer purchasing decisions, as faster delivery could lead to repeat orders and increased satisfaction.
6.	In-Analysis 
Unconfirmed Insights:
•	New York emerged as the best-performing city, likely due to product availability, customer demographics, and pricing strategies.
•	Company D performed exceptionally well, suggesting that offering discounts or loyalty incentives could further boost its revenue.
•	Beverage sales significantly outperformed other categories, possibly due to high demand trends or regional preferences.
•	Sales representatives in high-performing regions may be employing more effective strategies than those in lower-performing regions.

Recommendations
•	Implement targeted promotions in high-performing regions (North and East) to maximize revenue.
•	Offer loyalty discounts for Company D customers to encourage repeat purchases.
•	Increase inventory levels of top-selling products, particularly beverages, to meet demand without stock shortages.
•	Replicate December’s successful sales strategies in historically low-performing months.
•	Enhance training programs for underperforming sales representatives to align with top performers.
•	Consider establishing a headquarters in New York to leverage the strong sales performance and attract more customers.
Analysis Techniques Used in Excel:
•	Pivot tables: Used to aggregate sales revenue across regions, product categories, and time periods.
•	Trend Analysis: Month-over-month revenue comparisons were performed to detect sales fluctuations.
•	Data Filtering and Sorting: Enabled deep dives into customer purchasing behavior and transaction values.
•	Slicers: Added to pivot tables to allow for dynamic filtering of sales data based on different categories, such as region, product type, or customer segment.

7.	Post-Analysis and Insights
Findings:
•	Sales Trends: Sales data indicates a clear seasonal pattern, with noticeable revenue spikes during holiday periods.
•	Regional Performance: The North and East regions consistently generate the highest revenue, contributing 55% of total sales.
•	Top Customers: A significant portion of revenue (over 40%) is driven by repeat customers, highlighting the value of customer retention strategies over purely acquisition-based approaches.
•	Product Categories: Beverages and sauces remain the top-selling categories, contributing 30% of total revenue.
•	Sales Persons: The top 5 sales reps contribute nearly 50% of total sales, suggesting that training underperforming reps could yield significant gains.
•	Shipping Performance: Cities with efficient shipping networks correspond to higher revenue generation, indicating that logistical efficiency is a key driver of customer satisfaction and repeat purchases.
Comparison with Initial Findings:
•	Initial trends correctly indicated that certain product categories and regions dominate revenue generation, but further analysis revealed the importance of repeat customers and efficient logistics in sustaining high sales.
•	The assumption that revenue follows a linear trend was challenged by the discovery of seasonal fluctuations, emphasizing the need for demand forecasting and inventory adjustments.
•	The data showed that bulk transactions in metropolitan cities contribute significantly to revenue, a trend that was not immediately apparent in preliminary findings.
•	While it was initially suspected that all top-performing sales reps were assigned to high-revenue regions, further analysis indicated that individual sales strategies and customer relationships play a significant role.
•	There is a possible seasonal demand pattern, but further analysis is needed to establish whether external factors (e.g., holidays, promotions) influence these trends.
•	Certain sales representatives have significantly higher sales numbers—further investigation is required to determine whether this is due to individual performance, assigned regions, or customer relationships.
•	Some ship cities have higher transaction values, possibly indicating bulk purchases from corporate clients or regions with high disposable income.




