# Adventure-Workshop-Report-Power-BI 📊

 ## Project Overview

In this project, we aim to create an interactive and insightful report using Power BI. The report will cover various aspects of the Adventure Workspace data, providing valuable insights through different visualizations and analysis techniques.
Data Transformation through Power Query Editor

## 1. Merge Columns
- **Action:** Combine columns into one.
- **Steps:** Transform (existing) / Add Column (new column) → Merge Columns

## 2. Sort Column
- **Action:** Organize data in ascending or descending order.
- **Steps:** Home → Sort (A-Z / Z-A)

## 3. Append Queries
- **Action:** Combine rows from multiple tables into one.
- **Steps:** Home → Append Queries → Append Queries as new

## 4. Merge Queries
- **Action:** Combine columns from different tables.
- **Steps:** Home → Merge Queries → Merge Queries
- **Example:** Merging columns from [f-sales] and [d-product] using [productkey] as a common column.

## 5. Group By
- **Action:** Summarize data.
- **Steps:** Transform → Group By

## 6. Transpose Data
- **Action:** Swap rows and columns.
- **Steps:** Transform → Transpose

## 7. Reverse Rows
- **Action:** Reverse the order of rows.
- **Steps:** Transform → Reverse Rows

## 8. Count Rows
- **Action:** Count the number of rows.
- **Steps:** Transform → Count Rows

## 9. Format Data
- **Action:** Change the case, trim, clean, or add prefixes/suffixes.
- **Steps:** Transform → Format (lowercase / UPPERCASE / Capitalize Each Word / Trim / Clean / Add Prefix / Add Suffix)

## 10. Fill Down
- **Action:** Fill down missing values.
- **Steps:** Transform → Fill → Down

## 11. Fill Up
- **Action:** Fill up missing values.
- **Steps:** Transform → Fill → Up

## 12. Unpivot Columns
- **Action:** Transform columns into rows for analysis.
- **Steps:** Transform → Unpivot Columns

## 13. Split Column by Delimiter
- **Action:** Split a column based on a delimiter.
- **Steps:** Transform → Split Column → By Delimiter

## 14. Split Column by Position
- **Action:** Split a column based on position.
- **Steps:** Transform → Split Column → By Position

## 15. Parse JSON
- **Action:** Extract meaningful data from JSON.
- **Steps:** Transform → Parse [JSONResult] → JSON

## 16. Create Calendar Table
- **Action:** Build a calendar table to use dates as a primary key.
- **Steps:** Add Column → Day → Name of Day / Month → Start of Month / Month → Name of Month / Year → Year

## 17. Conditional Column
- **Action:** Create a column based on conditions.
- **Steps:** Add Column → Conditional Column

## 18. Custom Column
- **Action:** Create custom calculations.
- **Steps:** Add Column → Custom Column (e.g., generated Revenue)

## 19. Invoke Custom Function
- **Action:** Create and use a custom function.
- **Steps:** Home → New Source → Formula Bar { =(Price as number, Quantity as number) => Price * Quantity }

## 20. Column from Examples
- **Action:** Create columns based on examples.
- **Steps:** Column From Examples → From All Columns

## 21. Combine Files from Folder
- **Action:** Combine multiple files into one.
- **Steps:** Home → New Source → Folder → Select Path → Transform & Combine

## 22. Applied Steps
- **Action:** Track and manage changes.
- **Details:** Any deleted column in Power BI will be reflected in Power Query Editor with a step added to [Applied Steps] in [Query Setting].

## 23. Data Modeling in Power BI
- **Schemas:**
  - **Star Schema:** Fact table (descriptive data) and Dimension table (quantitative data).
  - **Snowflake Schema:** Used for normalization to reduce redundancy and improve data integrity.
  - **Model View:** Edit relationships and always use primary keys for accuracy. Avoid two-way filters with multiple fact tables.

## 24. DAX Functions
- **Examples:** Creating calculated columns and measures.
- **Functions:**
  - **IF:** Conditional statements.
  - **SWITCH:** Multiple conditions.
  - **RELATED:** Fetch related values from another table.
  - **SUMX:** Sum of an expression evaluated for each row.
  - **CALCULATE:** Evaluates an expression in a modified context.
  - **DATESYTD, PREVIOUSMONTH, DATEADD:** Time intelligence functions.

## 25. Building Reports
- **Visualizations:** Line & stacked column chart, doughnut chart, stacked bar chart, map, matrix, gauge chart, KPI, slicers, line chart (trend and forecast), area chart, tooltips, and more.
- **Interactivity:** Drill through, bookmarks, action buttons, custom visuals (e.g., scroller), Q&A, sync slicers, key influencers, decomposition tree.

## 26. Publishing Reports to Cloud
- **Steps:** Home → Publish → Save → Open in Power BI Service.

## 27. Gateways and Scheduled Refresh
- **Details:** Bridges gap for automatic data refresh between local and online data. Install gateway for scheduled refresh.

## 28. Incremental Refresh
- **Details:** Refresh only the latest data instead of the entire dataset, saving time.

