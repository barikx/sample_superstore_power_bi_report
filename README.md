# sample_superstore_power_bi_report

In this project, we'll embark on a thrilling journey, exploring every step from acquiring raw data to creating stunning reports with Power BI. Together, we'll uncover hidden insights and unleash the true power of data to make informed decisions. 

As we will be analyzing a sample superstore's sales report, By harnessing the robust functionalities of Power BI, We will be transforming raw data into stunning visualizations and report.

We'll start with a fresh Power BI project, and then we'll add a data source and report. By the end of this project, you'll have a full-blown Power BI project, ready to be used in your business.

The screenshot of the power bi report is shared below:


![bi](https://github.com/barikx/sample_superstore_power_bi_report/assets/124221384/4948b1dc-68c9-4656-add5-e0663cf3829b)

How the Sample Superstore Report is Created from an Excel File:

# Data Import:

Start by importing the Sample Superstore Excel file (.xlsx) into Power BI Desktop.

Load the tables such as Orders, Returns, and Users (depending on what's included).

Review the structure of the data (columns like Order ID, Customer Name, Region, Sales, Profit, etc.).

# Data Cleaning and Transformation:

Perform basic data cleaning:

Remove unnecessary columns.

Correct data types (e.g., dates, numbers, text).

Handle missing or null values if any.

Create calculated columns if needed (e.g., extracting year, month from order dates).

# Data Modeling:

Establish relationships between tables (for example, linking Orders to Returns using Order ID).

Ensure that the data model is clean, optimized, and follows a star schema where possible.

# Measure Creation (using DAX):

Create DAX Measures to calculate key metrics:

Total Sales (SUM(Sales))

Total Profit (SUM(Profit))

Profit Margin (DIVIDE(SUM(Profit), SUM(Sales)))

Number of Orders (DISTINCTCOUNT(Order ID))

Create time-based measures like Year-to-Date (YTD) Sales if needed.

# Building Visualizations:

Design various interactive visuals like:

Bar charts: Sales by Category, Sub-Category

Line charts: Sales/Profit trends over time

Maps: Sales by State/Region

Pie charts: Market Share by Segment

KPI Cards: Total Sales, Total Profit, Number of Customers

Use slicers and filters to allow users to select different regions, years, categories, etc.

# Dashboard Layout and Formatting:

Arrange visuals in a logical and clean layout.

Apply consistent color themes, fonts, and borders for a professional look.

Add titles, tooltips, legends, and labels for clarity.

# Interactivity Features:

Enable drill-through pages (e.g., click on a region to drill into detailed sales analysis).

Use bookmarks and buttons to navigate between report pages.

Set up dynamic titles that change based on selected filters.

# Publishing and Sharing:

Publish the report to Power BI Service for cloud access if needed.

Share the report link or embed it in dashboards for teams to use.

Summary Line for Resume:
"Built an interactive Power BI report by importing, cleaning, modeling, and visualizing Excel-based retail data (Sample Superstore), applying DAX measures, and delivering dynamic dashboards for business insight."

