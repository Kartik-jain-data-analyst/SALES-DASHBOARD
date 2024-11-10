# SALES-DASHBOARD

**Summary**
The dashboards provide a comprehensive view of sales data, segmented by various metrics such as product category, geographic location, age group, and time. The key insights include:

Sales Overview: Total sales, profit, average sales value, and average order value are prominently displayed, giving a high-level summary of business performance.
Sales by Product Category and Demographics: Visualization of sales data across product categories (e.g., Bikes, Accessories) and demographic groups (age groups like Youth, Adult).
Geographic Distribution: Revenue and sales distribution by state and country, highlighting top-performing regions.
Product Performance: Identifies top and bottom products by sales.
Trends Over Time: Line charts show yearly sales trends and monthly order quantities, helping to track growth patterns over time.

#################################################################################
#################################################################################

_**Steps to Create This Dashboard**__

**1. Prepare Data**
Collect the necessary data on sales, profit, product categories, customer demographics, order details, and geographic locations.
Clean the data to ensure it is free of duplicates or errors, and ensure all columns are in the correct format (e.g., dates, numeric values).

**2. Set Up the Dashboard Tool**
Choose a data visualization tool like Power BI, Tableau, or Excel.
Import your dataset into the tool. In Power BI, for example, use Get Data to load files from sources like Excel, SQL databases, or cloud storage.


3. Design Key Metrics and KPIs**
Total Sales, Profit, Average Sales Value, and Average Order Value: Use Cards or KPI visuals to display these key numbers.
Calculate these metrics in Power BI using DAX formulas:
Total Sales: SUM(Sales[SalesAmount])
Total Profit: SUM(Sales[Profit])
Average Sales Value: DIVIDE(SUM(Sales[SalesAmount]), COUNT(Sales[OrderID]))
Average Order Value: DIVIDE(SUM(Sales[SalesAmount]), COUNT(Sales[OrderID]))

**4. Create Data Visualizations**
Bar Charts for Revenue by Product Category and State:
Use Bar Chart visuals to show revenue by categories like product and state.
Drag the relevant columns (e.g., Product Category, State, Revenue) to the X and Y axes.
Pie Chart for Revenue by Age Group:
Add a Pie Chart visual and set age groups as slices, with revenue as the value.
Line Charts for Yearly Revenue and Monthly Orders:
Use Line Chart visuals to show trends over time, with date fields on the X-axis and revenue/order quantity on the Y-axis.

**5. Add Top and Bottom Product Visuals**
Create Horizontal Bar Charts for top and bottom products by sorting the data based on sales.
Filter the data to show the top and bottom 5 products.

**6. Set Up Filters and Slicers**
Add Slicers to enable users to filter data by date range, state, sub-category, etc.
For example, in Power BI, drag date fields to the slicer to create a date filter, allowing users to select custom ranges.

**7. Customize the Dashboard Design**
Apply a consistent color scheme and layout to improve readability (use brand colors if applicable).
Adjust font sizes, background colors, and label placements for clarity.

**8. Test and Publish**
Verify that all visuals update dynamically when filters are applied.
Publish the dashboard to a web platform or export it as a PDF for sharing.

#################################################################################
#################################################################################

**Top Dashboard: Sales Dashboard - Summary**
**Key Metrics:**

**Total Sales:** 85M
**Total Profit:** 32M
**Average Sales Value:** 754.37
**Average Order Value:** 11.90
Charts and Visuals:

Revenue by Product Category: A bar chart displays revenue across categories like Bikes, Accessories, and Clothing, with Bikes having the highest revenue at 62M.
Revenue by Age Group: A pie chart categorizes revenue by age group, with Adults (43M) generating the highest revenue.
Revenue by State: A bar chart shows revenue distribution across states, with California leading at 18M.
Total Sales by Country: A vertical bar chart displays sales by country, with the United States having the highest at 28M.
Yearly Revenue: A line chart presents revenue trends from 2011 to 2016, peaking in 2015 with 20M.
Top Product: A horizontal bar chart shows the top-selling products, with Water Bottles generating 0.8M.
Bottom Product: Another horizontal bar chart lists the lowest-selling products, with Mountain Bikes being the lowest at 50 units.


****Bottom Dashboard: Sales Dashboard - Sales Trend
Filter Panel:**

Allows filtering by date range, sub-category, and state.
Charts and Visuals:

Total Sales by Year: A line chart shows sales trends from 2011 to 2016, with a peak in 2015 at 20M.
Order Quantity by Month: A line chart illustrates monthly order quantities, with the highest in June at 138K.
Sales by Country: A bar chart shows total sales by country, with the United States leading.
Count and Percentage by Country: Bar charts display the order count and percentage distribution across countries.
Revenue by Product Category: Another bar chart showing revenue for Bikes, Accessories, and Clothing, similar to the summary dashboard.
