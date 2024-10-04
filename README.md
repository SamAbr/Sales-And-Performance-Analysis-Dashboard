# Sales and Performance Analysis Dashboard

## Description
This project leverages Power BI to deliver a series of dashboards analyzing multiple aspects of business performance. The dashboards focus on product line analysis, customer behavior, branch performance, city-wise insights, and time trends. Each visual provides a clear and interactive way to explore key metrics and support data-driven decision-making. 

## Skills and Tools
- Microsoft Power BI
- Data Exploration and Visualization
- KPI Analysis (Total Revenue, Average Ratings, Sales per Branch)
- Geographic and Temporal Data Mapping
- Dynamic Dashboards

## Key Insights
- **Product Line Performance:** Visuals compare revenue and customer ratings across different product lines, identifying high-performing and underperforming categories.
- **Customer Behavior:** Analysis reveals customer preferences and patterns, highlighting demographic trends and the impact of customer segments on sales.
- **Branch Performance:** Dashboard visualizes revenue distribution and branch-wise performance, showing disparities between various locations.
- **Time Trend Analysis:** A time series graph highlights trends over time, pinpointing significant fluctuations in key performance metrics.
- **City-Level Analysis:** Geographic maps and charts provide insights into city-level performance, revealing differences in customer engagement and revenue across cities.

## Overview and Findings
1. **Data Import:** The dataset was loaded into Power BI using the “Get Data” button under the “Data” group in the “Home” tab.
2. **Data Exploration:** 
   - A DAX formula was used to create a new measure called “Total Records,” showing a total of **1000 records**.
   - Among the three cities, **Yangon** recorded the most sales at **340**, followed by **Mandalay** (**332**) and **Naypyitaw** (**328**).
   - In branch performance, normal customers showed up more than members in branches A and B, while members were the most buyers in branch C.
   - The majority of buyers for fashion accessories, food and beverages, and sports and travel products were female, whereas male customers predominantly bought electronic accessories, home and lifestyle, and health and beauty products.

3. **Branch Performance Analysis:** 
   - The highest **COGS** was from **Branch C**, followed by Branch A and Branch B.
   - The average gross margin percentage for all branches was **4.76**.
   - Most total gross income came from **Branch C**, followed by Branch A and B.
   - Most products sold in food and beverage, electronic accessories, and fashion accessories were from **Branch C**, while Branch A led in home and lifestyle products and Branch B in sports and travel and health and beauty products.

4. **Product Line Analysis:**
   - The majority of revenue was from food and beverages, with health and beauty products generating the least.
   - Electronic accessories were the most popular products with **971 quantities sold**, while health and beauty had the least with **854 quantities sold**. Popularity was depicted using gradient color in the bars.
   - The relationship between average unit price and total quantities sold suggested no correlation, as total quantities sold decreased without following a consistent trend in average unit price.

5. **Customer Behavior Analysis:**
   - Most member customers were female, while most normal customers were male.
   - Member customers rated the products higher than normal customers.
   - The preferred payment method for member customers was credit cards, while normal customers favored the e-wallet system.

6. **Time Analysis:**
   - A line chart illustrated sales trends over working hours, indicating the peak sales hour was **7:00 PM**. The hour with the least sales was **5:00 PM**.

7. **City Analysis:**
   - A map displayed the distribution of total revenue among cities.
   - The average rating for Naypyitaw was the highest (**7.07**), while Mandalay had the lowest average rating (**6.82**).

## Recommendations
- **Branch C** is performing exceptionally well in terms of sales and gross income; the company should share best practices from this branch with others.
- The popularity of electronic accessories suggests that production methods leading to their success should be applied across all product lines.
- The peak sales hour at **7:00 PM** warrants hiring additional staff for Mandalay, while the working hours for Naypyitaw and Yangon are relatively balanced.
- Cities should adopt the customer engagement strategies of Naypyitaw, given its high ratings and total sales.

## Files Included
- `Performance_Analysis_Dashboard.pbix`: Power BI file containing all visualizations and dashboards for branch, product, customer behavior, time, and city analysis. It also includes the imported excel file which contains the data used for analysis.

## How to Use
1. Download the `.pbix` file and open it in Power BI Desktop.
2. Navigate through the different pages in the dashboard to explore branch performance, product analysis, and customer behavior.
3. Use filters and slicers to interact with the data and gain deeper insights into specific metrics.

## Contents
- **Page 1: Data Exploration**
- **Page 2: Branch Performance Analysis**
- **Page 3: Product Line Analysis**
- **Page 4: Customer Behavior Analysis**
- **Page 5: Time Trend Analysis**
- **Page 6: City-Level Insights**
