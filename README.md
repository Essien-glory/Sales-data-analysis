# Sales-data-analysis
This report shows the sales trends for various products in nine cities in the year 2019.

The Purpose of this project is to Analyze sales data to identify trends, top-selling products, and revenue metrics for
business decision-making.

**Data Cleaning Process**
1. Make the first row as headers.
2. Remove irrelevant column.
3. Use appropriate data types(Select the detect data type option in Transform tab)
4. Split the Order date column to date and time stamp(Using the Split to Column option, Split by delimeter)
5. Close & Apply.
![Screenshot 2024-07-29 105043](https://github.com/user-attachments/assets/e64f1d2e-e453-4f5e-8c41-b0d29e816de8)

![Screenshot 2024-07-29 105946](https://github.com/user-attachments/assets/d11f248c-279e-4868-a3cc-05fa33b6ed50)

**Analysis**
The table consists of these columns
Order Id
Product
Quantity ordered
Price each
Order date
Purchase address
Month
Sales
City
Hour

To extract the day & month from the date, i used the "DAY" & "MONTH" function

Day = DAY('Sales Data'[Order Date])
Month = MONTH('Sales Data'[Order Date])


![Screenshot 2024-07-29 101206](https://github.com/user-attachments/assets/769709f4-c9fd-41de-9850-4f7e52d9917f)

![Screenshot 2024-07-29 101158](https://github.com/user-attachments/assets/f33577d5-a517-4480-84eb-49fe18eaffc6)


**Visualization**
![Screenshot 2024-07-29 101051](https://github.com/user-attachments/assets/4e8fd649-99f9-48f4-ba20-57b516cf0145)


In analyzing the sales data, we have 9 cities, 19 products, and 1 year (2019).

Total sales amounted to $34,483,365.68.
Total quantity ordered was 209,038.

Key metrics: sales and quantity ordered.

The first chart shows the sales trend and quantity ordered per month. This reveals that December had the highest sales.
Chart 2 shows the top 10 products with the highest sales (MacBook Pro sells the most, followed by iPhone).
Chart 3 visualizes the location that made the most sales, which is San Francisco.
Using a trend line, you can drill down to see which day in the month achieved the highest sales.
Chart 5 shows the product that was ordered the most out of the 19.
Additionally, a map was used to show the locations in the United States with the highest sales. The bubble represents the sales (the bigger the bubble, the higher the sales).

You can make use of the filters to filter by year, month, and city. It is highly interactive.

