# E-commerce Sales Analysis (Excel Project)

This is my Excel project on e-commerce sales data. I cleaned the data, connected four sheets, made pivot tables and charts, and built a dashboard with slicers. At the end I wrote down what I found from the data.

## About the Data

The workbook has four sheets with about two years of orders (October 2023 to October 2025).

| Sheet | Rows | What it has |
|---|---|---|
| Sales_Fact | 2,000 | Order date, customer, product, store, quantity, price, discount, total amount |
| Customer_Dim | 500 | Name, age, gender, city, state, country |
| Product_Dim | 100 | Product name, category, sub-category, brand, cost, stock |
| Store_Dim | 20 | Store name, region, city, store type (Flagship, Outlet, Online) |

## Files in this Repository

| File | What it is |
|---|---|
| Excel work.xlsx | My final Excel file with the cleaned data, pivot tables, charts and dashboard |
| Ecommerce_Sales_Raw Dataset_updated .xlsx | The raw dataset before cleaning |
| Ecommerce_Sales_Analysis_Report.pdf | Report with the problem statement, screenshots of each step and insights |

## What I Did

1. **Data cleaning:** used Find and Replace for IDs and country names, PROPER, TRIM and CLEAN for names and cities, and IF and MEDIAN formulas to fill missing values.
2. **Data modelling:** made relationships between Sales, Customer, Product and Store in the Data Model, and used XLOOKUP to bring names into the sales sheet.
3. **Descriptive analysis:** descriptive statistics on Total_Amount, sales by category and sales by region.
4. **Diagnostic analysis:** sales by gender in each region, and sales by store type and category.
5. **Predictive analysis:** monthly sales trend from October 2023 to October 2025.
6. **Prescriptive analysis:** top 10 best-selling products.
7. **Dashboard:** all charts on one sheet with slicers for Category, Region, City, Store Type and Gender.

## Tools Used

- Microsoft Excel
- Pivot Tables and Pivot Charts
- Slicers
- Power Pivot (Data Model)
- XLOOKUP, IF, ROUND, MEDIAN, PROPER, TRIM, CLEAN
- Analysis ToolPak (Descriptive Statistics)

## Main Findings

- Total sales is about Rs. 21.74 lakh from 2000 orders, and the average order is about Rs. 1087.
- Sports and Electronics earn the most, and Beauty earns the least.
- North, South and East have almost equal sales, but the West is very low (about 12% of total sales).
- Female customers spend more than male customers in every region.
- Online stores sell the most, and Outlet stores sell the least.
- Monthly sales stay mostly between Rs. 90 thousand and Rs. 1 lakh, and the highest month is March 2025.

## How to Use

1. Download the repository or open the files from GitHub.
2. Open `Excel work.xlsx` in Excel.
3. Go to the dashboard sheet and click the slicers to filter the charts.
4. Read `Ecommerce_Sales_Analysis_Report.pdf` to see all the steps with screenshots.

## Author

Dhanush
GitHub: [dhanush6787](https://github.com/dhanush6787)
