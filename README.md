# 🍕 DOMINO'S PIZZA SALES | BUSINESS INTELLIGENCE DASHBOARD


Pizza Sales Analysis Dashboard
An end-to-end sales analysis project built using Power BI and the Pizza Sales dataset. The dashboard turns one year of transactional pizza-order data (January–December 2015) into a concise view of revenue, order volume, product mix, and best-selling pizzas.


Project Overview
The objective of this project is to analyze pizza sales performance and identify useful business patterns, including:
- Overall revenue and order performance.
- Daily and monthly order trends.
- Revenue contribution from each pizza category.
- Pizza sales distribution by size.
- The five best-selling pizzas by quantity.
Dataset
- File: pizza_sales.csv
- Period covered: January 1, 2015 – December 31, 2015
- Records: 48,620 order-line records
- Distinct orders: 21,350
The dataset includes fields such as pizza_id, order_id, pizza_name_id, quantity, order_date, order_time, unit_price, total_price, pizza_size, pizza_category, pizza_ingredients, and pizza_name.
Dashboard Highlights
Key Performance Indicators
KPI	Value
Total Revenue	$817,860.05
Average Order Value	$38.31
Total Orders	21,350
Total Pizzas Sold	49,574


1. Daily Order Volume
Day	Orders
Sunday	2,624
Monday	2,794
Tuesday	2,973
Wednesday	3,024
Thursday	3,239
Friday	3,538
Saturday	3,158


Friday recorded the highest order volume, while Sunday recorded the lowest.
2. Monthly Order Trend
Month	Orders
January	1,845
February	1,685
March	1,840
April	1,799
May	1,853
June	1,773
July	1,935
August	1,841
September	1,661
October	1,646
November	1,792
December	1,680


July had the highest number of orders (1,935), and October had the lowest (1,646).
3. Revenue by Pizza Category
Category	Revenue	Share
Classic	$220,053.10	26.91%
Supreme	$208,197.00	25.46%
Chicken	$195,919.50	23.96%
Veggie	$193,690.45	23.68%


Classic pizzas contributed the largest share of revenue.
4. Pizzas Sold by Size
Size	Quantity Sold	Share
Large (L)	18,956	38.24%
Medium (M)	15,635	31.54%
Small (S)	14,403	29.05%
X-Large (XL)	552	1.11%
XX-Large (XXL)	28	0.06%


Large pizzas accounted for the highest quantity sold.
5. Top 5 Best-Selling Pizzas
Rank	Pizza	Quantity Sold
1	The Classic Deluxe Pizza	2,453
2	The Barbecue Chicken Pizza	2,432
3	The Hawaiian Pizza	2,422
4	The Pepperoni Pizza	2,418
5	The Thai Chicken Pizza	2,371


Tools & Technologies
- Power BI Desktop – data modeling, DAX measures, and dashboard creation.
- Power Query – data import, type conversion, profiling, and transformation.
- DAX – KPI calculations and analytical measures.
- CSV – source dataset.
  
Data Preparation & Analysis Workflow
1. Imported the pizza sales CSV into Power BI.
2. Promoted the first row to column headers and checked column data types.
3. Used Power Query column profiling to inspect valid, error, empty, distinct, and unique values.
4. Created measures for revenue, order count, pizza quantity, and average order value.
5. Created day-name and day-number fields to analyze weekday order patterns in the correct weekday sequence.
6. Built visuals for daily and monthly trends, category revenue, pizza size, and the top five pizzas.
7. Compared dashboard figures with calculations from the source dataset.
Key Business Insights
- Friday is the busiest day by order count.
- July is the strongest month by order count in the dataset.
- Classic pizzas are the largest revenue-contributing category.
- Large pizzas account for the greatest share of pizzas sold.
- The Classic Deluxe Pizza is the top-selling pizza by quantity.
<img width="1672" height="941" alt="pizza_sales_dashboard_purple" src="https://github.com/user-attachments/assets/50599fd7-3582-46b7-95dd-7142c04975b8" />


- The figures in this README reflect the CSV-based calculations used for the dashboard.
If you find this project useful, feel free to star the repository.
