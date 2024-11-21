# Cookie Sales Analysis

## Data Cleaning and Integration Process

### Data Cleaning in Excel
1. Opened customer, orders, and cookie type CSV files in Excel.
2. Checked for misaligned columns, extra spaces, and unexpected characters.
3. Used Excel’s `Remove Duplicates` feature to eliminate duplicate entries.
4. Identified empty cells and filled missing values with placeholders where appropriate.
5. Converted dates to a consistent format and standardized text to proper case.
6. Deleted non-essential columns or rows.
7. Used Find and Replace to correct special characters and encoding issues.
8. **Save Cleaned Data**: Save the cleaned datasets as new CSV files.

### Data Integration Using Power BI
1. **Load Data into Power BI**: Import cleaned customer, orders, and cookie type files into Power BI Desktop.
2. **Transform Data**: Use Power Query Editor for additional data cleaning and transformation.
3. **Create Data Model**: Define relationships between tables:
   - Link customer table to orders table via CustomerID.
   - Link orders table to cookie type table via CookieTypeID.
4. **Design Visualizations**: Create visualizations like bar charts, pie charts, and line charts to represent cookie sales data.
5. **Build Interactive Dashboard**: Arrange visuals on the canvas, and incorporate slicers and filters for dynamic data exploration.
6. **Publish and Share**: Publish the dashboard to the Power BI service and share with stakeholders.

## Summary
This process ensures that the data is clean, well-structured, and ready for analysis. By leveraging Excel for initial data cleaning and Power BI for integration and visualization, we can create a comprehensive and interactive cookie sales dashboard.

