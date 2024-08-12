# Data Analyst Portfolio Projects of Eren Kirac
## Coffee Sales Analysis with Excel
---
### Introduction

This is an Excel project on coffee sales analysis of an **_imaginary store_**. The project is to analyze and derive insights to answer crucial questions and help the imaginary store to make data driven decisions.

---
### Problem Statement
1. #### Which coffee type sells the most?
   Understanding the most popular coffee type will allow the store to focus on promoting and stocking the right products
2. #### Which country and its top 3 cities have the highest sales?
   Identifying the geographical locations with the most sales can guide the store's marketing and expansion strategies.
3. #### Who are the top customers of the store, and which customers are most important?
   Analytzing customer data will help the store recognize its most valuable customers and tailor its offerings to retain them.
4. #### During which time period are sales the greatest, and what could be the reason ?
   Exploring the time periods with the highest sales will help the store understand seasonal trends and optimize its inventory and marketing efforts accordingly.
---
### Skills/Concepts Demonstrated
The following Excel features were incorporated:
- Various Excel Formulas,
- XLOOKUP,
- Relative/Absolute Cell Reference,
- INDEX, MATCH,
- IF/IFS,
- Pivot Tables/ Pivot Charts, Drill Down in Python Charts,
- Timeline, Slicer
---
### Data Transformation/Cleaning
Data Transformation/Cleaning

- **Customer Data Integration**: I used the XLOOKUP function to create and populate the customer name, email, country, city, and loyalty card columns by retrieving data from the customers table into the orders table.
![](https://github.com/kiraceren/Portfolio-Projects/blob/main/Excel%20Portfolio%20Project/columns_created.png)![](https://github.com/kiraceren/Portfolio-Projects/blob/main/Excel%20Portfolio%20Project/xlookup_func.png)
- **Product Data Integration**: I utilized the INDEX and MATCH functions to create the coffee type, roast type, size, and unit price columns, pulling the necessary data from the products table.\
![](https://github.com/kiraceren/Portfolio-Projects/blob/main/Excel%20Portfolio%20Project/new_columns.png) ![](https://github.com/kiraceren/Portfolio-Projects/blob/main/Excel%20Portfolio%20Project/index_func.png) 
- **Column Recreation**: I created new columns for coffee type name and roast type name by merging the coffee type and roast type data.

   Previous                                                                                                   |New
   :------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------:
   ![](https://github.com/kiraceren/Portfolio-Projects/blob/main/Excel%20Portfolio%20Project/coffe_roast.png) |![](https://github.com/kiraceren/Portfolio-Projects/blob/main/Excel%20Portfolio%20Project/coffee_roast_name.png)
- **Sales Calculation**: Created a sales column by multiplying the quantity by the unit price for each order.
  
   ![](https://github.com/kiraceren/Portfolio-Projects/blob/main/Excel%20Portfolio%20Project/sales.png)
---
### Visualization
The report includes four key visualizations:
1. A line chart showing total sales over time by date.

![](https://github.com/kiraceren/Portfolio-Projects/blob/main/Excel%20Portfolio%20Project/line_chart.png)

2. A bar chart displaying total sales by country.

![](https://github.com/kiraceren/Portfolio-Projects/blob/main/Excel%20Portfolio%20Project/ttl_by_country_bar.png)
 
3. A breakdown of total sales by the top 3 cities within each country.

![](https://github.com/kiraceren/Portfolio-Projects/blob/main/Excel%20Portfolio%20Project/drill_down_top_3_cities.png)
   
4. A chart highlighting the top 5 customers by sales.

![](https://github.com/kiraceren/Portfolio-Projects/blob/main/Excel%20Portfolio%20Project/top_5_bar.png)

[You can download the dashboard here](https://github.com/kiraceren/Portfolio-Projects/blob/main/Excel%20Portfolio%20Project/coffeeSalesPortfolioProject-ErenKirac.xlsx)\
[The data](https://github.com/kiraceren/Portfolio-Projects/blob/main/Excel%20Portfolio%20Project/coffeeSalesPortfolioProjectData.xlsx)

![](https://github.com/kiraceren/Portfolio-Projects/blob/main/Excel%20Portfolio%20Project/dashboard.png)

---

### Features
Timeline and slicers are utilized to filter data by time period, roast type, size, and customer loyalty card status.

![](https://github.com/kiraceren/Portfolio-Projects/blob/main/Excel%20Portfolio%20Project/timeline_slicers.png)

---
### Analysis
Highest Sales by Coffee Type and Month
- **Arabica**: $841 in September 2021
- **Liberica**: $844 in January 2022
- **Excelsa**: $681 in April 2019
- **Robusta**: $493 in September 2019

Highest Sales by Size and Country

- _Across all countries_, the highest sales were consistently for the 2.5 kg size.
---
### Conclusion,Recommendations
- US has the highest impact on income.
- The _2.5 kg_ size is the most profitable. It is advisable to focus on this size to maximize revenue.



---
Thanks to [Mo Chen](https://www.youtube.com/@mo-chen) for this guided project.
