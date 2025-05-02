# sample_superstore_power_bi_report

I shall devide this project in three sections. 
### Level 1 - Introduction
### Level 2 - Data Analysis
### Level 3 - Result

# 1. Introduction :

Download the excel file(which contains the data of sales of different products of a super store) from here - https://github.com/barikx/sample_superstore_power_bi_report/blob/main/Sample%20-%20Superstore.xlsx


We'll start with a fresh Power BI project, and then we'll add a data source and report. By the end of this project, you'll have a full-blown Power BI project, ready to be used in your business.

The screenshot of the power bi report after finishing of the project is shared below:


![bi](https://github.com/barikx/sample_superstore_power_bi_report/assets/124221384/4948b1dc-68c9-4656-add5-e0663cf3829b)


# 2. Data Analysis - How the Sample Superstore Report is Created from an Excel File:

## 📂 1. Data Source Connection
The Excel file (probably named like SampleSuperstore.xlsx) was imported into Power BI.

It contained raw data about:

Orders (Product, Category, Sub-Category)

Sales

Profit

Quantity

Region and State

Year / Date of order

✅ In Power BI:

➔ Click Home > Get Data > Excel Workbook ➔ Select the Excel file ➔ Load tables into Power BI.

## 🧹 2. Data Cleaning and Transformation (Power Query Editor)
Before creating visuals, they likely:

Renamed columns if needed for clarity.

Removed null values or empty rows.

Converted data types:
(e.g., Sales and Profit to Decimal Number, Quantity to Whole Number).

Created a "Year" field from the date if not already available.

✅ In Power BI:

➔ Use Transform Data to clean and prepare.

## 📊 3. Data Modeling (Relationships if needed)
If the Excel file had multiple sheets (like Customers, Orders, Products), relationships were created between:

Orders Table linked to Products Table (Product ID)

Orders Table linked to Customers Table (Customer ID)

✅ In Power BI:

➔ Go to Model View to set relationships.

## 📈 4. Creating Visualizations
Now comes the real dashboard building:

Cards for KPIs:

Sum of Sales (2.30M)

Sum of Profit (286.40K)

Sum of Quantity (38K)

Table for Region/Sub-category breakdown

Line Chart for Profit over Years (growth trend)

Bar Chart for Profit by Sub-Category

Pie/Donut Charts for:

Profit by Region

Profit by Segment

Profit by Category

✅ In Power BI:

➔ Use Visualizations Pane ➔ Drag and drop fields to create graphs.

## 🎛️ 5. Adding Filters / Slicers
Slicer for States:
Allows the user to select a specific state and update the whole dashboard dynamically.

✅ In Power BI:

➔ Insert a Slicer ➔ Choose State column.

## 🎨 6. Styling and Formatting
Black background for a modern dashboard look.

White text and bright colored charts for contrast.

Rounded and clean fonts to make it easy to read.

Proper titles for every visual.

✅ In Power BI:

➔ Use Format Pane ➔ Customize fonts, colors, backgrounds.

## 💾 7. Saving and Publishing
Saved as .pbix file (Power BI file).

Optionally, published to Power BI Service for sharing with others.



# 3. Result - What is the result which we shall get from this project?

## Key Insights from the Dashboard:

### 1. Overall Performance Metrics (Top Center)

Sum of Sales: 2.30 Million dollars

Sum of Profit: 286.40K dollars

Sum of Quantity: 38K units

👉 This tells us the overall sales revenue, total profit earned, and total quantity of products sold.

### 2. Profit Trend Over Time (Top-Right Line Chart)

Sum of Profit by Year (2016–2019):

2016: 50K

2017: 62K

2018: 82K

2019: 93K

👉 The profit has been steadily increasing year over year — a positive growth trend.

### 3. Profit Contribution by Region (Donut Chart)
   
West: 108.42K profit (37.86%) — highest

East: 91.52K profit (31.96%)

South: 46.75K profit (16.36%)

Central: 39.71K profit (13.82%)

👉 West region contributes the largest share of profits.

### 4. Profit Contribution by Customer Segment (Donut Chart)

Consumer: 134.12K (46.83%) — largest customer segment

Corporate: 91.89K (32.12%)

Home Office: 60.3K (21.05%)

👉 Consumers drive almost half of the total profits.

### 5. Profit by Product Category (Donut Chart)

Technology: 145.45K (50.79%) — most profitable category

Office Supplies: 122.49K (42.77%)

Furniture: 18.45K (6.44%)

👉 Technology products are the biggest contributors to profit.







