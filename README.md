# Cookie Sales Analysis

## Data Cleaning and Integration Process

### Data Cleaning in Excel
1. Opened customer, orders, and cookie type CSV files in Excel.
2. Checked for misaligned columns, extra spaces, and unexpected characters.
3. Used Excel’s Remove Duplicates feature to eliminate duplicate entries.
4. Identified empty cells and filled missing values with placeholders where appropriate.
5. Converted dates to a consistent format and standardized text to Propercase.
6. Deleted non-essential columns or rows.
7. Used Find and Replace to correct special characters and encoding issues.
8. Saved the cleaned datasets as new CSV files.

### Data Integration Using Power BI
1. Imported cleaned customer, orders, and cookie type files into Power BI Desktop.
2. Used Power Query Editor for additional data cleaning and transformation.
3. Defined relationships between tables by:
   - Linking customer table to orders table via CustomerID.
   - Linking orders table to cookie type table via CookieType.
4. Created visualizations like bar charts, column chart, table, and line charts to represent cookie sales data.
5. Arranged visuals on the canvas, and incorporated slicers and filters for dynamic data exploration.
6. **Publish and Share**: Publish the dashboard to the Power BI service and share with stakeholders.

 ### COOKIE SALES DASHBOARD ANALYSIS
![Sales Analysis](https://github.com/AyomideOkoya/Data_Cleaning_and_Interation_Process/blob/42b21ffe82ea1b0b6cd32a29230c98ec1f57c75f/cookies%20sales%20dashboard.png)
 

### Overview:
This dashboard provides a comprehensive view of cookie sales performance, with an extensive view of metrics like revenue, profit, and customer data. The primary KPIs include Total Sales, Total Profit, Number of Orders, Units Sold, and Profit Margin. The dashboard is designed to offer actionable insights through various visualizations and filters.


### Key Performance Indicators (KPIs):
Total Revenue: $4.69M
Total Profit: $2.72M
Number of Orders: 700
Units Sold: 1M
Profit Margin: 57.93%


### Visualizations:
**Product Profit Margin Table:**
Displays profit margins for different cookie types (e.g., Chocolate Chip, Fortune Cookie, Oatmeal Raisin).

**Profit Trend Over Time (Line Chart):**
Visualizes monthly profit trends, indicating seasonality and peak profit periods.

**Revenue by Customer (Bar Chart):**
Shows revenue contributions by top customers, highlighting key accounts.

**Number of Orders by Customer (Bar Chart):**
Illustrates the number of orders placed by each customer, identifying frequent buyers.

**Revenue and Profit by State (Bar Chart):**
Compares revenue and profit across different states, revealing geographic sales performance.


### Insights and Recommendations:

**Insight 1: Profit Trend Over Time**
**Observation:** The line chart shows significant profit peaks in September and November.
  **Recommendation:** Increase marketing efforts and promotions in these months to leverage higher sales volumes. Consider launching seasonal cookie varieties to attract more customers.

**Insight 2: Product Profit Margins**
**Observation:** Snickerdoodle has the highest profit margin (62.5%), while Fortune Cookie has the lowest (50%).
  **Recommendation:** Focus on promoting high-margin products like Snickerdoodle. Evaluate production costs for lower-margin products to find ways to improve profitability.

**Insight 3: Top Customers**
**Observation:** Customer 3 contributes the highest revenue ($1.43M) and has the highest orders (206).
**Recommendation:** Implement loyalty programs and personalized marketing strategies to retain and further engage top customers. Offer exclusive deals to high-value customers.

**Insight 4: Geographic Sales Performance**
**Observation:** States like Wisconsin (WI) and New York (NY) show the highest revenue and profit.
**Recommendation:** Concentrate marketing and sales efforts in high-performing regions. Investigate factors contributing to lower sales in other states and tailor strategies to boost performance.


### Conclusion:
By analyzing these key performance indicators and visualizations, we gain valuable insights into sales trends, customer behaviour, and product performance.
Implementing these recommendations will effectively optimize sales strategies, significantly enhance customer engagement, and drive overall profitability to new heights.
