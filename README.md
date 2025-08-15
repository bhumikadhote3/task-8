# task-8
Simple Sales Dashboard Design


# Task 8 - Sales Dashboard (PDF Output)

## Objective
The goal of this task was to create a basic sales dashboard using the given **Superstore** dataset. 
Instead of an interactive Tableau dashboard, a static PDF output with visualizations was generated.

## Dataset
- **File:** Superstore.xlsx
- **Key Columns Used:** Order Date, Region, Category, Sales, Profit

## Steps Performed
1. **Data Cleaning**
   - Removed '$' signs from Sales and Profit columns.
   - Converted data to numeric format.
   - Extracted `Month-Year` from `Order Date`.

2. **Data Aggregation**
   - **Sales Over Time:** Monthly total sales.
   - **Sales by Region:** Summed sales per region.
   - **Sales by Category:** Summed sales per category.

3. **Visualization**
   - **Line Chart:** Sales trend over months.
   - **Bar Chart:** Sales by region.
   - **Donut Chart:** Sales by category.

4. **PDF Export**
   - All charts compiled into a single PDF file: `TASK_8_Sales_Analysis.pdf`.

## Insights
1. **West region** had the highest overall sales.
2. **Technology** category contributed the largest share of sales.
3. Sales show **seasonal fluctuations**, with peaks in certain months.

## Files Included
- `TASK_8_Sales_Analysis.pdf` → PDF with charts.
- `README.md` → This documentation.


