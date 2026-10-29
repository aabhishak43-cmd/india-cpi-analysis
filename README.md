# india-cpi-analysis
India Consumer Price Index (CPI) analysis using Microsoft Excel to explore inflation trends and price movements.
# India CPI Analysis Using Microsoft Excel

# India CPI and Inflation Analysis Using Excel

# India CPI and Inflation Analysis Using Microsoft Excel

## Project Overview

This project analyzes India's Consumer Price Index (CPI) data using Microsoft Excel to investigate inflation trends,changes in consumer prices, and the relationship between global crude oil prices and domestic inflation.

The analysis covers CPI basket contributions, year-over-year inflation, food-price movements, inflation trends around the onset of COVID-19, and the relationship between monthly Brent crude oil price changes and CPI category movements.

The project demonstrates practical skills in data cleaning,Excel formulas, trend analysis, data visualization, and correlation analysis.

## Project Objectives

1. Identify the contribution of broader categories to India's CPI basket.
2. Analyze year-over-year CPI inflation trends from 2017 and identify the year with the highest inflation.
3. Investigate food inflation trends and identify the food sub-category with the largest absolute index-point change.
4. Compare inflation trends before and after the onset of COVID-19 in March 2020.
5. Examine the relationship between imported crude oil price changes and inflation across CPI categories.

## Tools and Technologies

- Microsoft Excel
- Excel Formulas and Functions
- Data Cleaning and Preparation
- CPI Trend Analysis
- Data Visualization
- CORREL Function
- Economic Data Analysis

## Dataset Information

### Consumer Price Index (CPI)

- Geographical Coverage: India
- Index Base: 2012 = 100
- Data Period: January 2013 – May 2023
- Sectors: Rural, Urban, and Rural+Urban (Combined)
- Data Format: CSV and Excel

The CPI dataset contains index values for categories including food and beverages, housing, fuel and light,health, education, transport and communication, and other consumer expenditure categories.

### Imported Oil Price Data

- Commodity: Brent crude oil
- Data Period: January 2021 – May 2023
- Unit: USD per barrel

The workbook references EIA/IMF global Brent crude oil price data. The exact source series should be verified before publication.

## Data Cleaning and Preparation

The raw CPI dataset was reviewed and incorporated into the analysis workbook.
The data preparation process included:

- Reviewing the dataset structure and column names.
- Examining date and category fields.
- Correcting month-label inconsistencies in the working data, including identified spelling and spacing issues.
- Preparing the data for monthly and year-over-year comparisons.
- Organizing CPI categories for broader category analysis.
- Preparing the relevant series for charts and calculations.
- Reviewing data availability and identifying missing observations.

The source data contains a gap for April 2019, as noted in the workbook. Missing observations were not treated as actual zero values.

## Project Workflow

1. Reviewed the raw CPI dataset and identified the relevant variables.
2. Prepared the data for analysis and corrected identified month-label inconsistencies.
3. Grouped related CPI categories into broader categories for the CPI contribution analysis.
4. Calculated broader category contributions for May 2023.
5. Analyzed annual average CPI index values and year-over-year inflation trends.
6. Examined monthly food-price movements over the 12 months ending May 2023.
7. Compared inflation trends before and after March 2020.
8. Compared monthly Brent crude oil price changes with CPI category changes using correlation analysis.
9. Summarized findings using Excel tables, calculations, and visualizations.

## Key Analysis Areas

### 1. CPI Basket Contribution Analysis

- Grouped CPI categories into broader expenditure categories.
- Examined the contribution of each broader category for May 2023.
- Used official CPI basket weights in the contribution methodology documented in the workbook.
- Identified food and beverages as the larges contributing category.

### 2. Year-over-Year Inflation Analysis

- Analyzed annual average CPI index movements from 2017 onward.
- Compared rural, urban, and combined CPI trends.
- Identified 2022 as the year with the highest combined annual inflation among the full years analyzed from 2017 to 2022.
- Researched potential economic factors, including global commodity price increases and the Russia-Ukraine war.

### 3. Food Inflation Analysis

- Examined monthly changes in the food and beverages index over the 12 months ending May 2023.
- Identified the months with the highest and lowest month-on-month index changes.
- Compared food sub-category index values between May 2022 and May 2023.
- Identified spices as the category with the largest absolute index-point increase over that comparison.

### 4. COVID-19 and Inflation Analysis

- Compared year-over-year inflation before and after the onset of COVID-19 in March 2020.
- Examined the General Index, food and beverages, health, and fuel and light.
- Compared average inflation over the 12 months before and after the selected onset date.
- Investigated changes in inflation patterns during the pandemic period.

### 5. Imported Oil Price and Inflation Correlation

- Analyzed monthly Brent crude oil prices from January 2021 to May 2023.
- Compared month-on-month oil-price changes with changes in selected CPI categories.
- Used Excel's CORREL function to measure the strength and direction of the relationships.
- Found that the observed correlations were weak across the categories examined.

## Key Findings

### CPI Basket Contribution

Food and beverages was the largest contributing category in the May 2023 analysis, with a calculated contribution of approximately 45.88% under the workbook's stated methodology.

### Year-over-Year Inflation

2022 recorded the highest combined annual inflation rate among the full years analyzed from 2017 to 2022,at approximately 6.62%, using the annual-average index methodology in the workbook.

### Food Inflation

- Highest monthly food and beverages index increase: October 2022, approximately 1.01%.
- Lowest monthly change: December 2022, approximately -1.35%.
- Largest absolute food sub-category index-point increase between May 2022 and May 2023: Spices, increasing by approximately 33.1 index points.

### COVID-19 and Inflation

Comparing the 12-month periods before and afte March 2020, the workbook found increases in averag year-over-year inflation for the General Index,food and beverages, and fuel and light.
Health inflation decreased over this particular comparison window. These findings describe the selected periods and do not establish that COVID-19 alone caused the changes.

### Oil Price Correlation

The workbook found weak correlations between month-on-month Brent crude oil price changes and month-on-month CPI category changes.

Housing had the highest calculated correlation among the five categories examined, at approximately 0.158. This indicates a weak positive relationship over the selected period, not a causal effect.

## Business and Economic Insights

The analysis highlights several important observations:

- Food and beverages accounted for the largest calculated contribution to the CPI basket.
- Inflation trends varied across years and expenditure categories.
- Food sub-categories experienced different price movements during the selected period.
- Inflation patterns differed across the selected pre-COVID and post-onset comparison windows.
- Monthly crude oil price changes did not show strong contemporaneous correlations with the selected CPI category changes.

These findings demonstrate how spreadsheet-based
analysis can help organize economic data, compare
trends, and investigate relationships between
economic indicators.

Correlation results should not be interpreted as
proof of causation.

## Project Files

- `All_India_Index_Upto_April23 (1)(1).csv`: Raw CPI dataset used as the source data for the project, subject to applicable redistribution terms.
- `CPI_Analysis.xlsx`: Excel workbook containing the executive summary, raw data worksheet, calculations, and five analysis worksheets.

## Limitations

- The analysis depends on the coverage and quality of the available datasets.
- The CPI dataset contains a missing observation for April 2019, as noted in the workbook.
- The 2023 annual inflation comparison uses only January to May observations and is not a full-year result.
- The imported oil-price analysis covers January 2021 to May 2023, not the entire year 2023.
- Correlation does not establish causation.
- Conclusions about economic events require supporting historical evidence and research.

## Conclusion

This project applies Microsoft Excel to investigate India's CPI basket, historical inflation trends,food-price movements, inflation around the onset of COVID-19, and the relationship between imported
crude oil prices and CPI category changes.
It demonstrates a structured approach to data preparation, quantitative analysis, visualization, and interpretation of economic indicators.

## Author

Abhishek Khandelwal