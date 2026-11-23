# Kenya Malaria Analysis (2015--2025)

## Project Overview

This project analyses malaria incidence patterns across Kenya from
**2015 to 2025**. It explores changes over time, seasonal patterns,
differences between counties, and the relationship between rainfall and
malaria incidence.

The analysis uses a county-level dataset containing 6,110 observations
across 47 counties. The main outcome measure is `incidence_per_1000`
(malaria incidence per 1,000 people).

## Research Questions

1.  How has malaria incidence changed in Kenya from 2015 to 2025?
2.  Which months recorded the highest and lowest average malaria
    incidence?
3.  Which counties recorded the highest and lowest average malaria
    incidence?
4.  Is there a relationship between rainfall and malaria incidence in
    Kenya?

## Dataset

The source dataset is an Excel workbook (`malaria_kenya.xlsx`). It
contains 6,110 records and includes fields such as:

-   `county` --- county name
-   `year`, `month`, and `date` --- time dimensions
-   `incidence_per_1000` --- malaria incidence per 1,000 people
-   `precipitation` --- rainfall measure
-   `temperature` --- temperature measure
-   `ndvi` --- Normalized Difference Vegetation Index
-   `itn_coverage` --- insecticide-treated net coverage
-   `transmission_state` --- transmission category/state
-   Additional environmental and lagged variables

The analysis period is 2015--2025 and covers 47 counties.

## Tools and Techniques

-   **Microsoft Excel** --- source data
-   **Python (pandas)** --- data preparation, grouping and summary
    statistics
-   **Tableau Public** --- interactive dashboard and visual exploration
-   **Microsoft PowerPoint** --- presentation of findings

The analysis uses: - Grouped averages by year, month and county - A line
chart to show annual trends - Monthly and county comparisons - A scatter
plot and Pearson correlation to examine rainfall and incidence

## Key Findings

### 1. Annual trend

-   Highest annual average: **2015 --- 14.37 per 1,000**
-   Lowest annual average: **2025 --- 8.68 per 1,000**
-   The average incidence declined by approximately **39.6%** between
    2015 and 2025.
-   There were small increases in 2018 and 2022, although the overall
    direction was downward.

### 2. Monthly pattern

-   Highest average month: **June --- 14.61 per 1,000**
-   Lowest average month: **December --- 5.71 per 1,000**

These are pooled averages across the study period.

### 3. County comparison

-   Highest county average: **Homa Bay --- 14.13 per 1,000**
-   Lowest county average: **Meru --- 7.76 per 1,000**

### 4. Rainfall relationship

The Pearson correlation between precipitation and malaria incidence was
approximately **+0.575**, indicating a moderate positive association in
the observations.

This result does **not** prove that rainfall causes malaria. Correlation
describes an association, and other environmental, demographic,
prevention and healthcare factors may also influence incidence.

## Overall Conclusion

The supplied dataset shows a downward trend in average malaria incidence
between 2015 and 2025, alongside clear differences by month and county.
June had the highest pooled monthly average, December the lowest, Homa
Bay the highest county average and Meru the lowest. Rainfall had a
moderate positive association with malaria incidence.

These findings may help identify seasonal and geographic patterns for
further investigation and planning. They should be interpreted as
descriptive results from the supplied dataset, not as proof of
causation.

## Dashboard and Presentation

The project includes: - A Tableau Public dashboard showing annual
trends, monthly patterns, county comparisons, transmission-level views
and rainfall versus incidence. - A PowerPoint presentation summarising
the research questions, methods, charts and findings.

## How to Use the Project

1.  Open `malaria_kenya.xlsx` to review the source data.
2.  Open the Tableau packaged workbook (`.twbx`) in Tableau Public to
    explore the dashboard.
3.  Open the PowerPoint presentation to review the project summary and
    findings.

File names may differ depending on the version saved or downloaded.


