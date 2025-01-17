# Maven Roasters Coffee Shop Data Analysis Interactive Dashboard Creation using Excel
##  Project Objective
A franchise owner at Maven Roasters, a coffee shop chain with three locations in New York City has collected transactional data from Jan-Jun 2023. 
Analyze and transform data into a dynamic dashboard that franchise owners can use to identify patterns, trends and opportunities for the business.

## Dataset Used
<a href="https://mavenanalytics.io/data-playground?order=date_added%2Cdesc&search=coffee%20shop">Coffee Shop Sales</a>

## Questions
-	How many transactions were recorded?
-	Over what period of time?
-	What products and product categories were sold?

<a href="https://github.com/hyperfabulous/Data-Analysis-Coffee-Shop-Sales-Dashboard/blob/main/coffee%20shop%20sales%20dashboard.png">view dashboard</a>

<a href="https://github.com/hyperfabulous/Data-Analysis-Coffee-Shop-Sales-Dashboard/blob/main/Astoria%20coffee%20shop.png">Astoria</a>

<a href="https://github.com/hyperfabulous/Data-Analysis-Coffee-Shop-Sales-Dashboard/blob/main/Hells%20kitchen%20coffe%20shop.png">Hell's Kitchen</a>

<a href="https://github.com/hyperfabulous/Data-Analysis-Coffee-Shop-Sales-Dashboard/blob/main/Lower%20Manhattan%20coffee%20shop.png">Lower Manhattan</a>

## Process
-	Add new columns to calculate Revenue (price * quantity), Month, Day of the week (display them as text instead of numerical values), and transaction Hours based on time.
-	Insert pivot tables on new tab to show Revenue by month, number of transactions by day of the week, hour of the day, by product category (sorted in descending order), and finally, number of transactions and revenue by product type (sorted in descending order and filtered to top 15, by transaction)
-	Add pivot charts to show revenue by month as Line chart; days of the week and hour of day as column chart; by product category as bar chart.
-	Add pivot table to show top 15 product types. 
-	Add slicer for store location and connect it to all pivot tables on the sheet.
-	Adjust formatting and polish to finalize dashboard.

## Dashboard
![coffee shop sales dashboard](https://github.com/user-attachments/assets/adbe4e46-0719-4ecb-9428-eb6fa1083b1d)
![Astoria coffee shop](https://github.com/user-attachments/assets/9345a24f-0b77-4a42-b938-d0a08d60f086)
![Hells kitchen coffe shop](https://github.com/user-attachments/assets/5e46144f-080a-4d4b-ae6d-0a7131b72e53)
![Lower Manhattan coffee shop](https://github.com/user-attachments/assets/29d0c04a-2537-43f6-a5e8-3df688ce6f5e)

## Project Insight
-	The month of June accounted for the highest revenue.
-	Mondays, Wednesdays, Thursdays and Fridays were days where significantly higher transactions were made.
-	The hours of 7am to 10am are the busiest hours of the day.
-	Coffee and Tea happen to be the most ordered Products.
-	Barista espresso, being fairly expensive and one of the most ordered, pulled in the highest revenue.

## Conclusion and Recommendations
  From the revenue trend across 6 months, Marvin Roasters coffee shop profit margin seem to be on a steady rise. However if any recommendation for further increase in revenue and profit margin is to be made,
-	Extra production cost and stock increase could be allocated towards the top selling product category (Coffee, Tea and Bakery).
-	Additional operating staff could be transferred from the late closing hours of the day (6pm-8pm) and added to the early working hours (7am-11am) to improve sales and transaction frequency, maximizing revenue.
-	Marketing campaigns to improve awareness of the availability of barista espresso could be made.
-	Discounted offers for underperforming products could also be implemented.






