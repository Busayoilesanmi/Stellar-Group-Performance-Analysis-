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
#### Datasets Used 
The dataset is a Grocery Store dataset which includes transaction records, customer details, product-related data, revenue, region, cities, and salespersons, etc.

#### Methods Used
The analysis utilizes Microsoft Excel tools, such as:

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

2.	Identification of Best-Selling Products:
   
•	The analysis pinpoints top-selling products, allowing businesses to focus on high-performing categories and allocate resources effectively.

•	Understanding which products generate the most revenue aids in demand forecasting and inventory management.

3.	Marketing Strategy Refinement:
    
•	Customer demographic insights help in segmenting the market and tailoring promotional campaigns.

•	By identifying the most profitable regions, businesses can optimize advertising spend and enhance customer engagement.

4.	Supply Chain and Logistics Optimization:
   
•	Evaluating sales by region and shipper performance helps streamline logistics, reducing costs and improving delivery efficiency.

•	Insights into shipping cities and revenue distribution assist in selecting better distribution centers and improving customer satisfaction.

5.	Strategic Business Expansion:

•	Regions with consistent high sales can be targeted for new store openings or increased marketing investments.

•	Understanding underperforming areas allows businesses to explore new strategies to improve penetration and sales.

By leveraging these insights, companies can increase revenue, reduce operational inefficiencies, and improve customer satisfaction, ultimately gaining a competitive advantage in the industry.
## Pre-Analysis 

### Identify Key Trends

•	Sales show fluctuations across months, indicating strong seasonality, likely influenced by external factors such as holidays, promotions, or economic conditions.

•	Certain regions consistently outperform others in revenue generation, suggesting geographical variations in consumer demand and purchasing power.

•	Repeat purchases from top customers indicate a loyalty pattern, which could be leveraged for personalized marketing strategies.

•	Sales representatives contribute differently to total revenue, highlighting possible performance gaps that may require further investigation.

### Potential Correlations

•	High sales concentration in specific product categories such as beverages suggests targeted consumer preferences, indicating that some product lines perform better than others across different regions.

•	A strong relationship between ship cities and revenue generation suggests that logistical efficiency and delivery times may influence purchasing decisions.

•	Certain sales reps are responsible for significantly higher sales such as Nancy freehafer, implying that sales performance may be impacted by factors such as customer relationships, experience, or region-specific demand.

•	Higher transaction amounts appear linked to specific customers, possibly indicating bulk buyers or corporate clients who contribute significantly to revenue.

### Initial Insights:
•	Beverages and sauces are top-selling categories, suggesting a strong consumer preference for consumables within the product mixtures.

•	The North and East regions contribute significantly to revenue, indicating these are key markets that should be prioritized for marketing and supply chain optimization.

•	Top 10 customers account for a significant portion of total sales, reinforcing the importance of customer retention strategies to maximize lifetime value.

•	Shipping efficiency and preferred shippers may influence customer purchasing decisions, as faster delivery could lead to repeat orders and increased satisfaction.

## In-Analysis 

### Unconfirmed Insights:

•	New York emerged as the best-performing city, likely due to product availability, customer demographics, and pricing strategies.

•	Company D performed exceptionally well, suggesting that offering discounts or loyalty incentives could further boost its revenue.

•	Beverage sales significantly outperformed other categories, possibly due to high demand trends or regional preferences.

•	Sales representatives in high-performing regions may be employing more effective strategies than those in lower-performing regions.

### Recommendations

•	Implement targeted promotions in high-performing regions (North and East) to maximize revenue.

•	Offer loyalty discounts for Company D customers to encourage repeat purchases.

•	Increase inventory levels of top-selling products, particularly beverages, to meet demand without stock shortages.

•	Replicate December’s successful sales strategies in historically low-performing months.

•	Enhance training programs for underperforming sales representatives to align with top performers.

•	Consider establishing a headquarters in New York to leverage the strong sales performance and attract more customers.

### Analysis Techniques Used in Excel

•	Pivot tables: Used to aggregate sales revenue across regions, product categories, and time periods.

•	Trend Analysis: Month-over-month revenue comparisons were performed to detect sales fluctuations.

•	Data Filtering and Sorting: Enabled deep dives into customer purchasing behavior and transaction values.

•	Slicers: Added to pivot tables to allow for dynamic filtering of sales data based on different categories, such as region, product type, or customer segment.

## Post-Analysis and Insights

### Findings

•	Sales Trends: Sales data indicates a clear seasonal pattern, with noticeable revenue spikes during holiday periods.

•	Regional Performance: The North and East regions consistently generate the highest revenue, contributing 55% of total sales.

•	Top Customers: A significant portion of revenue (over 40%) is driven by repeat customers, highlighting the value of customer retention strategies over purely acquisition-based approaches.

•	Product Categories: Beverages and sauces remain the top-selling categories, contributing 30% of total revenue.

•	Sales Persons: The top 5 sales reps contribute nearly 50% of total sales, suggesting that training underperforming reps could yield significant gains.

•	Shipping Performance: Cities with efficient shipping networks correspond to higher revenue generation, indicating that logistical efficiency is a key driver of customer satisfaction and repeat purchases.

### Comparison with Initial Findings:

•	Initial trends correctly indicated that certain product categories and regions dominate revenue generation, but further analysis revealed the importance of repeat customers and efficient logistics in sustaining high sales.

•	The assumption that revenue follows a linear trend was challenged by the discovery of seasonal fluctuations, emphasizing the need for demand forecasting and inventory adjustments.

•	The data showed that bulk transactions in metropolitan cities contribute significantly to revenue, a trend that was not immediately apparent in preliminary findings.

•	While it was initially suspected that all top-performing sales reps were assigned to high-revenue regions, further analysis indicated that individual sales strategies and customer relationships play a significant role.

•	There is a possible seasonal demand pattern, but further analysis is needed to establish whether external factors (e.g., holidays, promotions) influence these trends.

•	Certain sales representatives have significantly higher sales numbers—further investigation is required to determine whether this is due to individual performance, assigned regions, or customer relationships.

•	Some ship cities have higher transaction values, possibly indicating bulk purchases from corporate clients or regions with high disposable income.

## Data Visualizations & Charts

![Dashboard1](https://github.com/user-attachments/assets/2062c594-f3bd-4832-828d-2b70fa71ace6)

### Link to the excel Document

Excel File: https://docs.google.com/spreadsheets/d/1kaOiGDxFKQGRdCYy_v0D-BkVWhlfcijG/edit?usp=drive_link&ouid=104478848167416604596&rtpof=true&sd=true

•	Sales Trend Chart: This line chart illustrates seasonal variations in sales. A clear revenue spike is visible during holiday periods, confirming the impact of seasonal demand on sales volume.

•	 Top 10 Customers Bar Chart: This bar chart highlights the most valuable customers based on revenue contribution. The top 10 customers collectively generate 35% of total sales, emphasizing the importance of customer retention strategies.

•	Sales by Region Donut Chart: This donut visually represents revenue distribution across different regions. The North and East regions account for 65% of total revenue, making them the key markets for targeted business expansion.

•	Transaction by Amount Distribution Chart: This column chart shows the frequency of transactions across different sales amounts. It suggests that bulk transactions in metropolitan cities contribute significantly to total revenue.

•	Top 6 Ship Cities by Revenue Pie Chart: The pie chart demonstrates the proportion of revenue generated by the top 6 shipping cities. Fastest shipping cities correlated with 30% higher sales, showcasing the impact of logistics efficiency.

•	Sales by Representative Performance Bar Chart: This bar chart compares individual sales representatives' performance. Top-performing reps achieved 25% higher sales than the average, suggesting a need for targeted training and strategy replication.

•	Sales by Product Category Column Chart: This column chart compares product category performance. Top-Beverages contributed 40% of total sales, making them the most profitable category
.
•	Sales by Top 10 customer Bar Chart: This bar chart compares individual customer performance, Top 10 customers generated 35% of revenue, emphasizing the value of 
repeat customers.

## Recommendations and Observations
	
1.	Product Category Optimization
   
•	Expand high-performing categories: Since Beverages contribute 40% of total revenue, focus on expanding product offerings within this category. Introduce new beverage flavors or packaging sizes to cater to diverse customer needs.

•	Revise pricing for underperforming categories: Identify low-performing product categories and either rebrand, repackage, or adjust pricing to increase demand.

•	Inventory management improvements: With seasonal sales fluctuations, adjust stock levels to avoid overstocking low-performing products while ensuring high-selling products are readily available.

2.	Customer Retention & Targeting
   
•	Prioritize repeat customers: Since the Top 10 customers generate 35% of revenue, implement loyalty programs, exclusive discounts, or early product access to strengthen customer relationships.

•	Segment customer base: Leverage demographic insights to create targeted promotions based on customer location, purchase history, and product preferences.

•	Increase personalization in marketing: Use purchase patterns to personalize emails and promotions, enhancing customer engagement and driving higher conversion rates.

3.	Sales & Marketing Strategy Adjustments
   
•	Expand in high-revenue regions: Since North and East regions account for 65% of total revenue, focus marketing efforts and product distribution in these areas.

•	Leverage successful sales reps: Sales reps in top-performing regions achieved 25% higher sales than the average rep. Use their strategies to train underperforming teams and optimize sales processes.

•	Target peak seasons effectively: Based on seasonal sales spikes, align promotional campaigns and inventory adjustments with high-demand periods.

4.	Operational & Logistics Enhancements
   
•	Improve shipping efficiency: With fastest shipping cities generating 30% higher sales, invest in optimizing logistics networks to reduce delivery time and increase customer satisfaction.

•	Monitor supply chain bottlenecks: Ensure that products are always in stock and delivered efficiently to prevent revenue loss due to delays.
Unexpected Outcomes. 

•	Bulk transactions significantly influence revenue, suggesting that business-to-business (B2B) clients play a crucial role in overall sales performance. Creating exclusive B2B pricing models or bulk discounts may further drive revenue.

•	Sales were not evenly distributed among sales reps, indicating that individual performance and customer relationship management have a greater impact than regional assignments alone.
•	Higher revenue concentrations in urban locations suggest that targeted promotions in metropolitan areas could maximize returns.

## Conclusion

### Findings
•	New York's strong sales performance may be driven by product availability, customer demographics, and pricing strategies.

•	Company D performed exceptionally well, indicating that targeted discounts and loyalty incentives could boost future sales.

•	Beverage sales outperformed other categories, suggesting strong consumer demand in this segment.

•	Effective sales strategies in high-performing regions should be replicated in lower-performing areas.

•	Nancy Freehafer is the best Salesperson in the organization for the year

### Limitations

•	Data availability constraints may limit deeper insights into customer behavior.

•	Incomplete demographic details restrict customer segmentation.

•	Manual data entry and system errors may impact data accuracy.

•	Lack of marketing expenditure data limits understanding of promotional impacts.

### Future Research
•	Incorporate customer segmentation analysis to enhance targeting strategies.

•	Explore pricing optimization models to improve profitability.

•	Analyze customer retention patterns to develop long-term engagement strategies.

•	Integrate real-time data tracking for more accurate and responsive sales forecasting.

### References & Appendices

### References:

•	Internal company sales records

•	Excel functions: Pivot Tables

•	Industry reports on retail and e-commerce trends

### Appendices

1.	Data Cleaning
Cleaning the dataset ensures accuracy and consistency in the analysis.

•	Removing Duplicates:
•	Used Remove Duplicates in Excel (Data → Remove Duplicates).

•	Handling Missing Values:
•	Used Find & Replace (Ctrl + H) to replace blank cells with placeholders or interpolated values.

•	Used Go To Special (F5 → Special → Blanks) to identify missing values.

•	Standardizing Text Formatting:
Applied TRIM(A1) to remove unnecessary spaces.

•	Used PROPER(A1), UPPER(A1), and LOWER(A1) to standardize capitalization.

•	Correcting Date Formats:
•	Applied TEXT(A1, "YYYY-MM-DD") to ensure consistency.

2. Data Transformation
Transforming data helps in extracting useful insights.

•	Aggregating Sales Data by Month, Region, and Category:

•	Created Pivot Tables for quick summarization.

•	Pivot tables were used to: 

•	Aggregate sales by product category.

•	Compare regional performance.

•	Identify trends over time.

3.	Data Splitting
Separating dependent and independent variables for focused analysis.

•	Sales Revenue as Dependent Variable:

o	Analyzed using trend analysis and correlation tests.

•	Independent Variables:

o	Regions, product categories, and order dates were analyzed for impact on revenue trends.







