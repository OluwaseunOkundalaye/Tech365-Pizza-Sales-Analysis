# Tech365-Pizza-Sales-Analysis
An Excel project analyzing a year's worth of sales from a fictitious pizza sales place. The dataset encompasses details such as pizza type, size, quantity, price, and ingredients. The goal is to derive actionable insights to inform strategic decisions and optimize overall operational effectiveness.

## Table of Contents
- [Project Overview](https://github.com/OluwaseunOkundalaye/Tech365-Pizza-Sales-Analysis#project-overview)
- [Project Scope](https://github.com/OluwaseunOkundalaye/Tech365-Pizza-Sales-Analysis#project-scope)
- [Project Objectives](https://github.com/OluwaseunOkundalaye/Tech365-Pizza-Sales-Analysis?tab=readme-ov-file#project-objectives)
- Expected Outcome
- Document Purpose
- Use Case
- Data Source
- Data Cleaning and Processing
- Data Analysis
- Data Visualization
- Recommendation
- Conclusion

## Project Overview
This project involves an in-depth analysis of a year's worth of sales data from a fictitious pizza place. The analysis is performed using Excel, providing valuable insights to drive strategic decisions and optimize operational effectiveness.

## Project Scope
The project covers a comprehensive analysis of pizza sales, including order details, orders, pizza types, and pizzas. The analysis spans a full year, providing a detailed view of operational performance during this period.

## Project Objectives
The primary objectives of this analysis are:
-	**Sales Analysis:** Understand sales patterns over the year, identifying peak times and high-demand periods.
-	**Product Performance:** Evaluate which types and sizes of pizzas are most popular and generate the most revenue.
-	**Customer Preferences:** Analyze ingredient popularity and preferences to refine the menu offerings.
-	**Operational Insights:** Uncover inefficiencies and areas for improvement in operations and supply chain management.

## Expected Outcome
The analysis aims to provide actionable insights, including:
-	Daily customer count.
-	Identification of peak hours.
-	Average number of pizzas per order.
-	Identification of bestsellers.
-	Revenue analysis.
-	Detection of seasonality in sales.
-	Recommendations on menu optimization and promotional strategies.

## Document Purpose
This documentation serves as a guide for project stakeholders, providing insights into the project's objectives, data sources, data analysis, visualizations, and other relevant information.

## Use Case
Stakeholders Benefiting from the Analysis

**1.	Business Owners and Management**
-	**Decision-Making Support:** Provides insights into sales trends, product performance, and customer preferences for informed strategic decisions.
-	**Revenue Optimization:** Identifies high-demand products and peak sales periods, enabling targeted promotions and optimized pricing strategies.

**2.	Marketing Team**
-	**Targeted Campaigns:** Enables the development of targeted marketing campaigns based on customer preferences and popular products.
-	**Promotional Strategies:** Assists in designing effective promotional strategies to maximize impact during peak sales periods.

**3.	Operational Team**
-	**Staffing Efficiency:** Helps make better staffing decisions by identifying peak sales times.
-	**Process Improvement:** Provides a basis for process improvements to enhance productivity and service quality.

This comprehensive analysis equips each stakeholder with the insights needed to drive business growth, improve operational efficiency, and enhance customer satisfaction.

## Data Source
The dataset for this project is sourced from Maven Analytics [website](https://app.mavenanalytics.io/datasets?search=pizz) designed specifically for practice purposes. It is presented in an Excel file with four tables (Order Details, Orders, Pizza Types, and Pizzas) comprising 48,620, 21,350, 32, and 96 rows respectively, and 4, 3, 4, and 4 columns respectively. The dataset includes key attributes essential for a comprehensive analysis, such as:


![](https://github.com/OluwaseunOkundalaye/Tech365-Pizza-Sales-Analysis/blob/main/Number%20of%20Customers%20Per%20Day.png)

![](https://github.com/OluwaseunOkundalaye/Tech365-Pizza-Sales-Analysis/blob/main/Dashboard.png)


_My name is OLuwaseun Okundalaye_


```Day Number = WEEKDAY(sales[Date].[Date])```

``` SQL
UPDATE 
	Financial_Consumer_Complaints
SET 
	Timely_Response = 'In progress'
WHERE
	Timely_Response IS NULL
```


```SQL
SELECT 
	Month_Name,
COUNT 
	(Complaint_ID) AS [Total No of Complaints]
FROM
	Financial_Consumer_Complaints
GROUP BY 
	Month_Name, 
	Month_Number
ORDER BY 
	Month_Number ASC
```

| Month Name | Total Sales | Manager |
| ---------- | ----------- | ------- |
| Jan | 200 | Young |
| Feb | 500 | Seun |
| Mar | 100 | Tope |
| Apr | 800 | Nelson |


| Month_Name | Total No of Complaints |
|------------|------------------------|
| January    | 4883                   |
| February   | 4602                   |
| March      | 5335                   |
| April      | 5386                   |
| May        | 5608                   |
| June       | 5575                   |
| July       | 6474                   |
| August     | 5684                   |
| September  | 4765                   |
| October    | 4902                   |
| November   | 4626                   |
| December   | 4676                   |
