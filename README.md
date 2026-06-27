# Sales Performance Analysis with Excel

## Project Overview

This project is an Excel-based sales data analysis project. It focuses on analyzing sales performance using descriptive statistics, Pivot Tables, slicers, Power Query, Conditional Formatting, dashboarding, and VBA macro automation.

The goal of this project is to turn raw sales data into useful business insights and generate automated PDF reports based on regions.

## Objectives

The main objectives of this project were:

* Analyze the dataset using comprehensive descriptive statistics
* Visualize central tendency and dispersion indicators
* Create interactive analysis using Pivot Tables and slicers
* Analyze total sales by region and product type using Power Query
* Apply Conditional Formatting to highlight the top 10% of sales records
* Create a VBA Macro to generate PDF reports for each region
* Build an Excel-based reporting workflow from raw data to final business reports

## What Was Done

In this project, the following tasks were completed:

### 1. Data Preparation

The raw dataset was reviewed and prepared for analysis. A cleaned version of the data was created to make the analysis more organized and reliable.

### 2. Descriptive Statistics

Comprehensive descriptive statistics were calculated for key numerical columns, including sales-related fields. This helped summarize the dataset and understand the distribution of important business metrics.

### 3. Central Tendency and Dispersion Analysis

Measures such as average, minimum, maximum, standard deviation, and other statistical indicators were analyzed and visualized using charts.

A slicer was also used to allow filtering based on sales type.

### 4. Pivot Table Analysis

Pivot Tables were used to summarize and analyze the data from different business perspectives, such as:

* Sales by region
* Sales by product type
* Sales by sales channel
* Product performance comparison
* Regional performance comparison

### 5. Power Query Transformation

Power Query was used to calculate total sales by region and categorize the results based on product type.

This step helped transform and summarize the data in a more structured way for business analysis.

### 6. Conditional Formatting

Conditional Formatting was applied to highlight the top 10% of sales records in green.

This made it easier to quickly identify high-performing sales records.

### 7. Dashboard Creation

An interactive Excel dashboard was created using Pivot Tables, charts, and slicers.

The dashboard allows users to explore sales performance visually and filter the analysis based on different dimensions.

### 8. VBA Macro Automation

A VBA Macro was created to automatically generate PDF reports for each region.

Each PDF report includes sales amount and count based on product type and sales type.

This automation reduces manual reporting work and makes the reporting process faster and more efficient.

## Tools Used

* Microsoft Excel
* Power Query
* Pivot Tables
* Slicers
* Charts
* Conditional Formatting
* VBA Macro
* PDF Export Automation

## Project Structure

```text
sales-performance-analysis-excel/
│
├── README.md
│
├── workbook/
│   └── excel-sales-analysis.xlsm
│
├── reports/
│   ├── sample-region-report-1.pdf
│   ├── sample-region-report-2.pdf
│   └── sample-region-report-3.pdf
│
└── screenshots/
    ├── dashboard.png
    ├── descriptive-statistics.png
    └── power-query-result.png
```

## Dashboard Preview

![Dashboard Preview](screenshots/dashboard.png)

## Reports Preview

The `reports` folder contains sample PDF reports generated automatically by the VBA Macro.

Each report is created based on a specific region and includes summarized sales information by product type and sales type.

## Key Skills Demonstrated

* Data Cleaning
* Descriptive Statistics
* Business Data Analysis
* Excel Dashboard Design
* Pivot Table Analysis
* Power Query
* Conditional Formatting
* VBA Automation
* Automated PDF Reporting
* Data Storytelling

## Notes

The main workbook is a macro-enabled Excel file with the `.xlsm` format.

To use the VBA macro and generate PDF reports, download the workbook and open it in Microsoft Excel with macros enabled.

GitHub may not preview Excel macro-enabled files directly, so screenshots and sample PDF reports are included to make the project easier to review.

## Conclusion

This project demonstrates how Microsoft Excel can be used as a complete data analysis and reporting tool. It covers the full workflow from data preparation and statistical analysis to dashboard creation and automated PDF reporting.
