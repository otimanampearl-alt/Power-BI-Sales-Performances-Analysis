# Sales Performance Analysis Dashboard | Power BI

## Project Overview

This project is a Power BI sales performance dashboard developed during my Franova internship. It analyses sales performance across 2024 and 2025, with a focus on overall sales, year-on-year growth, returns, monthly trends, and regional sales-versus-target performance.

The project demonstrates my practical use of **Power BI data modelling, table relationships, DAX measures, and interactive dashboard design**.

## Project Objective

The objective was to bring data from multiple files into a connected data model and build a dashboard that helps users monitor sales performance, compare periods, assess returns, and review regional performance against targets.

## Data Model

The Power BI model contains seven tables:

1. `Fact_Sales`
2. `Fact_Returns`
3. `Sales_Targets`
4. `Dim_Calendar`
5. `Dim_Product`
6. `Dim_Staff`
7. `Dim_State_Region`

The model separates transactional/fact data from descriptive/dimension tables. This structure supports analysis across time, products, staff, and geographical regions.

The supplied PBIX confirms these seven model tables. The exact relationship columns and cardinalities are not described here because they should be read from the Model view in Power BI rather than guessed from the dashboard visuals.

## Methodology

### 1. Data consolidation and modelling

- Brought the project data into Power BI from multiple source files.
- Organised the data into seven fact and dimension tables.
- Created a relationship model to support analysis across the connected tables.
- Used the calendar, product, staff, and state/region dimensions to provide descriptive context for sales and returns.

### 2. DAX and KPI development

The report uses measures for key performance indicators, including:

- Total Sales
- Return Rate %
- YOY%
- Returned Quantity
- Sales Vs Targets Variance %

The PBIX report layout confirms these measure names are used by the dashboard. The DAX expressions themselves are not reproduced in this README; they should be copied from the model's measure definitions in Power BI if the exact formulas need to be documented.

### 3. Dashboard creation

The report contains a Sales Performance Dashboard for 2024–2025, with:

- KPI cards for Total Sales, Return Rate %, and YOY Growth %.
- A monthly sales trend comparing 2024 and 2025.
- A pie chart showing returned quantity by return reason.
- A regional bar chart showing Sales Vs Targets Variance %.
- Interactive slicers for Region, Month, and State.
- A written summary to guide interpretation of the dashboard.

## Dashboard Highlights

The dashboard screenshot and report configuration show the following displayed KPI values:

| KPI | Displayed value |
|---|---:|
| Total Sales | 347.75M |
| YOY Growth % | 1.13 |
| Return Rate % | 0.02 |

Other dashboard views include:

- Monthly sales comparison for 2024 and 2025.
- Returned quantities grouped by return reason.
- Sales-versus-target variance percentage by region.
- Region, month, and state slicers for interactive filtering.

The return-reason chart displays six categories: Damaged item, Changed mind, Quality issue, Wrong item delivered, Late delivery, and Better price found elsewhere.

## Business Insights

The dashboard is designed to help a business:

1. **Monitor overall sales:** The Total Sales KPI provides a high-level view of sales performance.
2. **Compare year-on-year performance:** The YOY measure and monthly comparison make it possible to review changes between 2024 and 2025.
3. **Understand product/customer return reasons:** The return-reason breakdown highlights the categories contributing to returned quantities.
4. **Review regional target performance:** The regional variance chart helps identify differences in performance against sales targets.
5. **Explore performance interactively:** Region, month, and state slicers allow users to focus on selected parts of the business.

These are analytical uses of the dashboard. Specific causes of sales changes or returns would require further investigation of the underlying data and should not be inferred from the visuals alone.

## Recommendations

Based on the dashboard's analysis areas, the business could:

- Review monthly sales movements to understand periods of stronger or weaker performance.
- Investigate regions with lower sales-versus-target variance and identify practical ways to improve performance.
- Track return reasons over time and investigate recurring issues, especially those related to product quality, damaged items, and incorrect deliveries.
- Use the calendar and regional dimensions to support consistent period and location comparisons.
- Review the definitions and formatting of the YOY Growth and Return Rate measures so that KPI values are clearly interpreted by dashboard users.

## Tools and Skills Demonstrated

- **Power BI Desktop** — report development and dashboard design.
- **Power Query** — data preparation and loading.
- **Data modelling** — organising seven fact and dimension tables into a relationship model.
- **DAX** — KPI and analytical measure development.
- **Data visualization** — KPI cards, line chart, pie chart, and regional bar chart.
- **Interactive reporting** — slicers for Region, Month, and State.

## Conclusion

This project strengthened my understanding of how data from multiple sources can be organised into a connected Power BI model and transformed into an interactive sales performance dashboard.

It demonstrates my ability to work across the Power BI process: data preparation, data modelling, DAX-based measures, visualization, and business-focused reporting.
s---

*Project: Franova Sales Performance Dashboard | Reporting period: 2024–2025*
