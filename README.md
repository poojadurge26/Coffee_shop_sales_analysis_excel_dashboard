# Coffee_shop_sales_analysis_excel_dashboard
Problem Statement
Analyze sales records and build a Dashboard for a coffee shop using Excel. Identify trends, patterns, and insights that can inform strategic decision-making and enhance business performance. The objective is to explore various aspects of sales data, including product performance, peak sales periods, and revenue trends, to uncover actionable insights that can improve sales strategies.


Key Questions

The primary business problem addressed in this project is the need for a detailed analysis of the coffee shop's data. Key questions include:
1.	How do sales vary by day of the week and hour of the day ?
2.	Are there any peak times for sales activity ?
3.	What is the total sales revenue for each month ?
4.	How do sales vary across different store locations ?
5.	What is the Average Price Per Order ?
6.	Which products are the best selling in terms of Quantity & Revenue ?
7.	How do sales vary by Product Category and Size ?

   
Data Cleaning and Transformation

In Power query editor,
• Reviewing each column to get a good grasp of the data and understand its context within the domain. This helps in recognizing errors, inconsistencies and important information related to the coffee shop's operations. • Abbreviations such as "Lg," "Rg," and "Sm" were used to represent the size of products in the "product_detail" column. But instead created a new column named "size" to provide a clearer representation of product sizes. Sm >> Small , Rg >> Regular , Lg >> Large
• Leading and Trailing spaces were eliminated from all columns, enhancing the cleanliness and uniformity of the dataset • The “transaction_time” column underwent a refinement process where date values were removed, leaving only the time in HH:MM:SS format.
• A new custom column named "Total_bill" was created by multiplying the “unit_price” and “transaction_qty” for each entry. This addition provides a comprehensive overview of the total sales generated from each transaction.
• Extracting the “day of the week” and “month name” from the "transaction_date" column allows for a detailed analysis of how sales fluctuate across different days and months. Similarly, extracting the “hour of the day” from the "transaction_time" column enables the identification of peak sales hours.


Results

Busiest Days and Times:
• The busiest hours for coffee sales are between 8:00 AM and 10:00 AM, indicating strong demand during morning rush hours. • Mondays and Fridays tend to have the highest sales volumes, indicating increased demand at the beginning and end of the workweek.
Percentage share based on Size:
• Large-sized drinks dominate the sales representing the preferred choice among customers while Small-sized drinks are the least contributed.
Comparable Footfall Distribution:
• All stores exhibit almost similar level of foot traffic throughout the months, indicating a balanced distribution of customers across different locations. Similar footfall levels present equal opportunities for sales and revenue generation across all stores.
Percentage share based on Category:
• Coffee and Tea Categories account for the largest percentage share of sales which is about 67% with Coffee being the most contributed(38%).
Top Products
• Barista Espresso emerges as the best-selling product, reflecting a strong demand for coffee among customers followed by Brewed Chai Tea ranks as the second-highest selling product.


Key Takeaways

	Issues in the current situation 
o	The product category Packaged Chocolates is the least selling category.
Possible Solution: If there is not much profit in this category, stop it’s production but if there is a good profit margin you should apply discount schemes or try selling it in a combo with the most relatable category.
o	In every store, generally the sales decrease to its half after 11 in the morning.
Possible Solution: Start renting out chambers in the cafe after 11 at a discounted price as there is less rush that time.
o	In Astoria the sales in the month of February are the least even it’s the Valentine month.
Possible Solution: Start new seasonal discount schemes offering discounts and special gifts to selected lucky customers. 
o	In Lower Manhattan the Sales are highest on Mondays and relatively very less on the other days.
Possible Solution: Introduce weekday schemes and offer discounts on weekends.
Give discount coupons on Mondays which can be claimed on weekends.
o	In Lower Manhattan the Overall Sales are very less.
Possible Solution: Organize events and extra activity programs in the Café so that it creates awareness among the people of the locality and they reach on to you.

![Coffeeshopsalesanalysis](https://github.com/poojadurge26/Coffee_shop_sales_analysis_excel_dashboard/assets/42688025/8ec70f41-fcff-4190-b30f-3a2c7f983f2e)
