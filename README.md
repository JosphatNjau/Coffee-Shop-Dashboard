# Coffee Shop Sales Dashboard

## Project Overview
This project involves building an interactive dashboard using Excel to analyze and visualize sales data for a fictional coffee shop in New York City. The dashboard provides insights into sales patterns, customer behavior, and product popularity, enabling the coffee shop to make informed decisions for improving operations and customer experience.

## Data Source
- **Dataset**: Transaction records from a fictional coffee shop in New York City
- **File Format**: Excel (.xlsx)
- **Structure**: Single table with 149,116 records and 11 fields

## Tools Used
- **Excel**: For data cleaning, data analysis, and dashboard creation
- **Pivot Tables**: Used for summarizing key metrics and performing exploratory data analysis
- **Pivot Charts**: Used for visualizing trends and identifying patterns in the data

### Data Preparation
1. Examined the dataset to understand the transaction period, types of products sold, and product categories.
2. **Adding Calculations**:
   - Added a new column for revenue, calculated as `price * quantity`.
   - Created columns to extract and display transaction month and day of the week as text (e.g., “Jan”, “Mon”) using the following functions:
     - To extract month ```=TEXT(B2,"mmm")```
     - To extract hour `=TEXT(B2,"ddd")`
   - Extracted the hour from the transaction time to analyze transaction patterns by hour of the day.
     - `=HOUR(E2)`

### Data Exploration with Pivot Tables
1. Created a Pivot Table to show revenue trends across each month.

      ![Revenue by month](https://github.com/user-attachments/assets/495dfff2-1a53-4983-90ac-3cdf8dd99f54)
   
2. Analyzed transaction volume by day of week and hour to identify peak times.

   ![Transaction by day of week](https://github.com/user-attachments/assets/23574376-199c-4ae2-a3f1-854a5172f5ff)

   ![Transaction by hour of day](https://github.com/user-attachments/assets/3fb4324f-d8b7-4042-993b-266a00d32fb9)

3. Created a summary to show transaction counts by product category, helping identify popular categories.

   ![Transaction by product category](https://github.com/user-attachments/assets/1523c77d-4517-49a4-99d4-c1a2dda51e62)

4. Filtered data to show the top 15 products by transaction count, including associated revenue.

   ![Top 15 products](https://github.com/user-attachments/assets/5573c02f-83d8-4040-a721-ca853ce5f296)

### Dashboard Creation
1. **Visualizations**:
   - A line chart showing revenue trends by month.
   - A column chart to illustrate which days are busiest.
   - A column chart showing peak transaction hours.
   - A bar chart highlighting the most popular product categories.
   - A table showing the top-selling products.
2. **Interactive Features**:
   - **Location Slicer**: Allows filtering by coffee shop location (Astoria, Hell’s Kitchen, Lower Manhattan).
3. **Final Layout**: Organized the charts and tables into a clean layout with alignment and formatting adjustments for a professional look.

![Coffee Shop Dashboard](https://github.com/user-attachments/assets/2b02352b-d64f-4443-965e-a89e8cbac726)

## Analysis & Insights
The dashboard reveals several key insights:
1. **Revenue Growth**: Revenue steadily increased from January to June, with the highest earnings in June.
2. **Peak Sales Day**: Monday recorded the highest transaction count, indicating it as the busiest day of the week.
3. **Busiest Hours**: Most transactions occurred between 6 AM and 11 AM, showing a preference for morning purchases.
4. **Popular Product Categories**: Coffee and bakery items were the most popular categories.
5. **Top-Selling Products**: Items like Barista Espresso and Gourmet Brewed Coffee were among the top-selling products in both transaction count and revenue.

## Recommendations
Based on the insights, here are actionable recommendations for the coffee shop:
1. **Increase Morning Staff**: Adding more staff from 6 AM to 11 AM can help accommodate the higher volume of morning customers and reduce wait times.
2. **Monday Promotions**: Introducing a "Monday Special" can capitalize on the high foot traffic on Mondays.
3. **Expand Bakery Options**: Considering the popularity of bakery items, expanding the bakery menu or introducing seasonal pastries may attract more customers.
4. **Promote Best Sellers**: Highlighting popular items like Barista Espresso and Gourmet Brewed Coffee through marketing materials can drive further sales.
5. **Loyalty Program**: Implementing a loyalty program for frequent customers, especially those visiting in the morning, can encourage repeat business.

### Conclusion
This dashboard provides a comprehensive overview of the coffee shop's performance, helping to identify trends, peak times, and popular products. By acting on the recommendations, the coffee shop can potentially improve operational efficiency, customer satisfaction, and overall revenue.

---

### Files in This Repository
- **Coffee_Shop_Dashboard.xlsx**: Contains the original dataset with calculated columns and PivotTables used to build the dashboard.
- **Dashboard Screenshot.png**: Screenshot of the final dashboard for quick reference.

### How to Use This Dashboard
1. **Download** the Excel file and open it in Excel.
2. Navigate through the PivotTable sheets to explore data insights.
3. Access the dashboard sheet to view all the visualizations and interact with slicers.
4. Adjust the slicer for "Location" to view data specific to each store location.

