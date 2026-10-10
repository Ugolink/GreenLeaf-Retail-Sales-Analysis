GREENLEAF RETAIL STORES NIGERIA

Sales Performance Analysis Dashboard

A Microsoft Excel Data Analytics Capstone Project
Prepared by: Faith Osakwe
Dataset period: January–December 2025
Documentation date: September 2026
Cohort: Data Analytics Community Group
Tool: Microsoft Excel

Transforming retail sales data into actionable business insights.

1. Title Page

This project documents the analysis of GreenLeaf Retail Stores Nigeria’s 2025 sales data using Microsoft Excel. The goal is to turn transaction-level records into a clear, interactive dashboard that supports sales-performance review and business decisions.

2. Dashboard Preview

GreenLeaf Retail Stores Sales Dashboard

Figure 1. The dashboard presents six KPI cards, four charts, a branch slicer, and a key-insights panel.

Dashboard components

• KPI cards: Total Sales, Total Discount, Discount %, Total Quantity, Total Transactions, and Average Order Value.
• Branch analysis: Total Sales by Branch and Sales & Discount Rate by Branch.
• Category analysis: Sales by Product Category.
• Time analysis: Monthly Sales Trend.
• Interactivity: A branch slicer allows users to explore branch-level performance.

3. Table of Contents

1. Title Page
2. Dashboard Preview
3. Table of Contents
4. Project Overview
5. Business Problem Statement
6. Project Objectives
7. About the Dataset
8. Tools & Technologies Used
9. Data Cleaning Process
10. Dashboard Wireframe
11. Key Insights
12. Business Recommendations
13. Conclusion
14. Appendix / GitHub Repository

4. Project Overview

This project uses transaction-level retail sales data for January–December 2025 to build an interactive Microsoft Excel dashboard. It summarizes sales, discounts, quantity, transaction count, average order value, branch performance, product-category performance, and monthly sales patterns.

The dashboard is intended to help users compare branches, identify high-performing categories, review monthly movement, and explore discount patterns. The displayed results report ₦152,589,401 in total sales, 1,500 transactions, and 9,614 units sold.

5. Business Problem Statement

Retail managers need a consolidated view of sales performance across branches, product categories, discounts, and months. Without a common report, it can be difficult to identify leading locations, understand category contribution, assess discount patterns, and spot stronger or weaker periods.

Business question: How can GreenLeaf use its 2025 sales data to understand performance across branches, categories, discounts, and months, and identify practical opportunities for improvement?

6. Project Objectives

• Summarize overall performance using sales, discounts, quantity, transaction count, and average order value.
• Compare branch sales and identify the leading branch.
• Compare sales contributions by product category.
• Review monthly sales patterns and identify high and low periods.
• Compare branch discount rates and recommend follow-up actions.

7. About the Dataset

The dataset covers January–December 2025. Project notes described the dataset as 1,537 rows and 13 columns, but the supplied worksheet screenshot visibly shows more than 13 field headings. The definitive column count should be confirmed against the Excel workbook before publication.

|Field visible in the worksheet|Description                                     |
|------------------------------|------------------------------------------------|
|Transaction ID                |Transaction identifier.                         |
|Date                          |Date of the transaction.                        |
|Branch                        |Store or branch associated with the transaction.|
|Region                        |Region associated with the branch.              |
|Product Category              |Category of the product sold.                   |
|Product Name                  |Name of the product.                            |
|Quantity                      |Units sold in the transaction.                  |
|Unit Price (NGN)              |Price per unit in naira.                        |
|Discount (%)                  |Discount rate recorded.                         |
|Total Sales (NGN)             |Sales value recorded for the transaction.       |
|Payment Method                |Payment type recorded.                          |
|Sales Rep                     |Sales representative recorded.                  |
|Customer Type                 |Customer classification recorded.               |
|Gross Sales (NGN)             |Gross sales value shown in the worksheet.       |
|Discount Amount               |Discount value shown in the worksheet.          |


8. Tools & Technologies Used

• Microsoft Excel: data organization, PivotTables/PivotCharts, KPI calculations, dashboard layout, and branch slicer.
• GitHub: project repository and publication of the dashboard, screenshots, and documentation.
• Markdown: formatting this project documentation in the repository README.

9. Data Cleaning Process

The supplied worksheet screenshot is labelled “GreenLeaf Retail Sales (CLEANED)” and shows a structured table with transaction, date, branch, product, quantity, price, discount, payment, sales representative, customer type, and sales-value fields. The screenshot does not establish exactly which cleaning operations were performed, so this section distinguishes visible evidence from checks requiring confirmation.

Visible preparation evidence

• Column headers and filter controls are present in a structured worksheet.
• The Date field is displayed in a date format.
• Sales and price fields are labelled in Nigerian naira (NGN), while Discount (%) is a separate field.
• Some visible categorical values read “Unknown”; their intended meaning and treatment should be verified.

Validation checklist for the workbook

• Check duplicate Transaction IDs and investigate repeated IDs.
• Review blanks and “Unknown” entries in categorical fields.
• Confirm dates are valid and within the intended period.
• Check that quantities, unit prices, sales, and discount amounts are numeric and valid.
• Validate the relationship between quantity, unit price, gross sales, discount amount, and total sales.
• Record each actual cleaning decision and include before-and-after examples where available.

Only describe a cleaning operation as completed after confirming it from the workbook or your working notes.

10. Dashboard Wireframe

The final dashboard places six KPI cards across the top, branch and discount comparisons in the middle, category and monthly-trend charts below, and the branch slicer and key-insights panel on the right. This hierarchy presents headline performance first, followed by comparisons and a way to filter the results.

A separate pre-build wireframe image was not supplied. This section therefore describes the completed dashboard layout; if an original PowerPoint sketch exists, it can be added to the images folder and linked here.

11. Key Insights

The following findings are based on values visible in the dashboard screenshot and project notes; amounts are rounded for readability.

• Overall performance: ₦152,589,401 in total sales across 1,500 transactions, with 9,614 units sold and an average order value of approximately ₦101,726.
• Leading branch: Kano recorded the highest branch sales at approximately ₦26.25 million.
• Leading category: Groceries generated approximately ₦30.34 million in sales, the highest category total shown.
• Monthly peak: January recorded the highest monthly sales at approximately ₦14.86 million, followed by October at approximately ₦14.26 million.
• Discount rate: Enugu had the highest displayed branch discount rate at 4.70%.
• Total discount: ₦5,898,974. The dashboard displays Discount % as 4%, a rounded figure; confirm the exact calculation and denominator before external reporting.

12. Business Recommendations

• Branch managers: Review Kano’s sales performance, product availability, and sales practices to identify approaches that may be useful elsewhere.
• Category managers: Monitor grocery stock and demand patterns. Compare other categories to find products that may benefit from promotions or assortment changes.
• Regional and finance teams: Review Enugu’s 4.70% discount rate against sales outcomes and margin targets. Confirm that discounts are approved and effective.
• Marketing team: Investigate factors behind the January and October peaks before repeating seasonal or promotional activities.
• Operations and analytics: Track the same KPIs monthly and validate sales and discount formulas for reliable comparisons.

These are suggested actions based on the dashboard patterns. Further operational data is needed to confirm the causes behind the results.

13. Conclusion

This project consolidates 2025 sales data into an interactive Excel dashboard for monitoring branch, category, discount, and monthly performance. The displayed results identify Kano as the leading branch, Groceries as the leading category, January as the strongest month, and Enugu as the branch with the highest displayed discount rate.

Before decisions are made, the underlying workbook and cleaning history should be validated. Potential next steps include profit/margin analysis, product-level performance, year-over-year comparisons, and linking sales patterns with stock or campaign data.


Author: Faith Osakwe
Focus: Data Analytics | Excel | Power BI | SQL
