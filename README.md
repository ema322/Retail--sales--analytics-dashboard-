# Adidas US Interactive Sales Dashboard
--------

##<img width="575" height="290" alt="Screenshot 2026-10-11 230340" src="https://github.com/user-attachments/assets/ae1471ca-5123-4afb-b685-5df7e8d82d0a" />

------
An interactive Excel dashboard for exploring Adidas sales performance by
region, product, sales method, and quarter. The dashboard summarizes key
metrics and uses PivotTables, PivotCharts, and filters to make sales
information easier to explore.

## Project Overview

This project turns sales data into a visual report that helps users
review performance across markets and products.

### Main goals

-   Summarize units sold and total profit.
-   Compare profit and discount by region.
-   Review product-level profit.
-   Compare sales methods such as Online, Outlet, and Retail.
-   Explore quarterly profit trends.
-   Make the dashboard interactive with region filters.
  

## Tools Used

-   Microsoft Excel
-   PivotTables
-   PivotCharts
-   Slicers / report filters
-   Dashboard layout and KPI cards

## Project Stages

### Stage 1 --- Define the business questions

The dashboard is designed to answer: - How many units were sold? - What
is the total profit? - How many retailers are represented? - How do
profit and discounts compare across regions? - Which products contribute
profit? - How do sales methods compare? - How does profit change by
quarter?

### Stage 2 --- Prepare the data

Before building the dashboard: 1. Review the source dataset and column
names. 2. Check for blank values, inconsistent labels, and duplicate
records. 3. Ensure fields such as region, product name, sales method,
quarter/date, profit, discount, and units sold use appropriate data
types. 4. Decide how missing values should be handled. 5. Keep a clean
copy of the original data for reference.

> Adjust these steps to match the exact cleaning work performed. Do not
> claim a cleaning step was completed unless you actually performed it.

### Stage 3 --- Create PivotTables

Build PivotTables to summarize: - **Units sold:** Sum of units sold. -
**Total profit:** Sum of profit. - **Retailers:** Count of distinct
retailers, if supported by the dataset. - **Sales methods:** Sales
totals grouped by sales method. - **Profit by product:** Sum of profit
grouped by product name. - **Profit and discount by region:** Sum of
profit and sum of discount grouped by region. - **Profit by quarter:**
Sum of profit grouped by quarter.

Use the aggregation that matches each question. A count of product names
is not the same as units sold, and a count of retailers is not
necessarily a distinct retailer count.

### Stage 4 --- Build charts

The dashboard contains visualizations for: - **Sales Methods:** Doughnut
chart comparing sales methods. - **Total Profit per Product:** Bar chart
comparing product-level profit. - **Profit and Discount by Country:**
Horizontal bar chart comparing regional totals. - **Profits per
Quarter:** Chart showing profit over time.

Use clear titles, readable labels, consistent formatting, and remove
blank categories where appropriate.

### Stage 5 --- Create KPI cards

Display headline metrics across the top: - Units Sold - Profit -
Retailers

Verify that each KPI uses the correct aggregation and responds as
intended to filters.

### Stage 6 --- Add interactivity

Add a region slicer or filter so users can select markets such as Egypt,
Iraq, KSA, Lebanon, and Oman.

If the dashboard uses multiple PivotTables, connect the slicer to all
relevant PivotTables through **Slicer \> Report Connections** (or
**PivotTable Connections**, depending on the Excel version). Test each
selection and confirm that the charts and KPIs update correctly.

### Stage 7 --- Format the dashboard

-   Use a consistent colour palette and font style.
-   Align charts and KPI cards.
-   Avoid overlapping labels and unnecessary legends.
-   Use descriptive chart titles.
-   Keep filters easy to find.
-   Remove blank categories when they are not meaningful.
-   Check that chart axes and number formats are readable.

### Stage 8 --- Validate and test

Before sharing: 1. Compare KPI values with the source data and
PivotTables. 2. Test every slicer option. 3. Confirm that relevant
charts update when a region is selected. 4. Check for blank categories
and missing labels. 5. Verify chart titles, totals, number formats, and
date/quarter ordering. 6. Save and reopen the workbook to ensure the
dashboard still works.

## Dashboard Components

  -----------------------------------------------------------------------
  Component                           Purpose
  ----------------------------------- -----------------------------------
  Units Sold KPI                      Summarizes the total units sold

  Profit KPI                          Displays total profit

  Retailers KPI                       Displays retailer count according
                                      to the chosen counting method

  Region slicer                       Filters the dashboard by region

  Sales Methods chart                 Compares Online, Outlet, and Retail

  Product profit chart                Compares profit across products

  Regional profit and discount chart  Compares profit and discount totals
                                      by region

  Quarterly profit chart              Shows profit trends by quarter
  -----------------------------------------------------------------------

## How to Use the Dashboard

1.  Open the Excel workbook.
2.  Use the region slicer to select one or more regions.
3.  Review the KPI cards and charts after each selection.
4.  Clear the filter to return to the overall view.
5.  Explore differences between regions, products, sales methods, and
    quarters.

## Key Considerations

-   **Profit and discount may use different scales.** Consider a
    separate chart if their values differ substantially.
-   **Blank categories:** Filter or investigate blank region/product
    values rather than silently deleting valid records.
-   **Retailer count:** Confirm whether the KPI is a row count or a
    distinct count of retailer IDs.
-   **Quarterly analysis:** Ensure quarters are sorted chronologically,
    not alphabetically.
-   **Business conclusions:** Add findings only after validating them
    against the underlying dataset.

## Suggested Repository Structure

``` text
adidas-us-interactive-sales-dashboard/
├── README.md
├── Adidas_US_Interactive_Sales_Dashboard.xlsx
└── images/
    └── dashboard-preview.png
```

Update the workbook filename and add a dashboard screenshot if you
include them in the repository. Do not upload confidential or restricted
data.



The final deliverable is an interactive Excel dashboard that organizes
sales metrics and comparisons in one view. It demonstrates data
summarization, PivotTables, PivotCharts, KPI reporting, filtering, and
dashboard design.


