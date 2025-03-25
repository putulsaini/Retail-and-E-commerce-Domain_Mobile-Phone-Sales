# Retail Sales Dashboard: Visualizing Insights with Power BI

***Objective***:

- To analyze mobile phone sales data using Power BI, providing actionable insights into sales trends, customer preferences, and payment methods within the Retail and E-commerce domain.

## Summary:

This Power BI project analyzes mobile phone sales data extracted from Kaggle and Excel. The data was cleaned, transformed using Power Query, and visualized using interactive dashboards. Key metrics like Total Sales, Total Quantity, MTD, QTD, and Year-over-Year comparisons were derived using DAX formulas. Insights reveal sales performance trends, preferred brands, and payment methods. The dashboard offers a comprehensive view for data-driven decision-making.

![Part-1 img](https://github.com/user-attachments/assets/97c4115b-f48c-48de-928f-bd17b2e8613c)


### STEPS : -

1. Data Extraction & Transformation

2. Custom Calendar & Data Modeling

3. Key Metrics Using DAX Formulas

3. What I Did in This Project

4. MTD Report Insights

5. Sales Trend Analysis by Month

6. Customer Ratings Overview

7. Payment Methods & Brand Performance

8. Conclusion and Business Recommendations

9. Thank You for Viewing!

### Key Highlights:

- Created a Custom Calendar table in Power Query.

- Developed multiple insightful visualizations using charts like Bar, Cluster, Pie, Line, Map, Area, Funnel, and more.

**Implemented powerful DAX Formulas for accurate insights, including:

- Transaction: COUNTROWS(Sales_Data)

- Total Quantity: SUM(Sales_Data[Units Sold])

- Total Sales: SUMX(Sales_Data,Sales_Data[Units Sold]*Sales_Data[Price Per Unit])

- Same Period Last Year: CALCULATE([Total Sales], SAMEPERIODLASTYEAR(Custom_Calender[Date].[Date]))

- Rating Status: IF(Customer Ratings >= 4, "Good", IF(Customer Ratings > 2, "Average", "Poor"))

- QTD and MTD Calculations

- Average Price: AVERAGE(Sales_Data[Price Per Unit])

## What I Did in This Project:

- Extracted data from Kaggle and Excel.

- Cleaned and transformed the data using Power Query.

- Created a Custom Calendar for time intelligence calculations.

- Applied DAX Formulas to generate meaningful insights.

- Designed an interactive Power BI Dashboard with various visualizations.

## Key Insights:

📌 MTD Report:

- MTD saw an impressive 4,777.85% increase from Jan 1, 2022, to Dec 31, 2022.

- The highest MTD jump of 23.70% occurred between Dec 26, 2022, and Dec 31, 2022.

![Part-2 img](https://github.com/user-attachments/assets/7f8425de-48b1-4b01-8119-adaf1842a329)


📌 Dashboard Report:

- July recorded the highest Total Quantity at 1700 units, 17.16% higher than February.

- The top brands in terms of sales were Apple, OnePlus, and Samsung.

- UPI and Credit Cards emerged as the most used payment methods.

📌 Yearly Comparison:

- Sales have shown consistent growth from 2021 to 2023.

- The total sales in 2023 were significantly higher compared to the previous years.

- The comparison with the same period last year shows a noticeable increase in revenue.

📌 Quarterly Performance:

- Quarter 4 (Q4) consistently performed the best across all years, indicating a strong sales trend during the holiday season.

- The growth in Q3 and Q4 compared to the same period last year highlights effective sales strategies.

📌 Monthly Insights:

- Monthly sales remained relatively stable, but a significant surge was observed in the last quarter of 2023.

- The comparison bars show that almost every month in 2023 outperformed the previous years, reflecting positive growth.

![Part-3 img](https://github.com/user-attachments/assets/21426b1f-27f4-41aa-a7af-dc22918e2961)


### Conclusions:

***Sales Growth:***

- The MTD sales showed a 4,777.85% increase from the beginning to the end of the year, indicating a successful marketing strategy or seasonal demand.

***Peak Sales Month:***

- July had the highest Total Quantity at 1700 units, which may suggest successful promotions or product launches during this period.

***Payment Preference:***

- Customers preferred UPI and Credit Card payments, making up a significant portion of the transactions. This suggests the need to continue offering digital payment options.

***Brand Dominance:***

- Apple, OnePlus, and Samsung dominated sales, indicating strong brand preference. Other brands may need targeted campaigns to increase their market share.

***Rating Insights:***

-Most customer ratings were Good (4+), suggesting overall customer satisfaction. However, focusing on the feedback from Average and Poor ratings can help further improve satisfaction.

### Business Recommendations:

***Seasonal Promotions:***

- Plan aggressive marketing campaigns and exclusive product launches in July to maximize revenue during the peak season.

***Expand Digital Payment Partnerships:***

- Strengthen partnerships with UPI and Credit Card providers to offer cashback, discounts, or loyalty rewards.

***Competitor Analysis:***

- Conduct a detailed analysis of competitor pricing and features to understand why certain brands outperform others.

***Product Quality Improvement:***

- Analyze customer feedback from Poor and Average ratings to address product or service issues.

***Diversify Product Range:***

- Consider expanding product offerings or introducing budget-friendly models to attract price-sensitive customers.

***Geographical Targeting:***

- Focus on cities with lower sales by introducing localized promotions or enhancing product availability.

### These recommendations will help optimize sales strategies, improve customer satisfaction, and strengthen market presence. 





