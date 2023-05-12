# AutoAnalysis
Preliminary Analysis of General Motors and Ford Motor company. 

**File Breakdown:**
* Data to Action presentation (.pptx) - Documents all major findings after analysis of both GM and Ford
* Data to Action Databricks export (.html) - Filtered data from S&P Global 
* Data to Action Source code (.rmd) - Source code files 

## Overview
This analysis demonstrates the following:
* Ability to work with the S&P Global platform.
* Transform data using SQL, Alteryx, and R. 
* Synthesize big data into insight and action.

## Approach
The approach to this analysis was to first, export all relevant data from the S&P Global database using SQL. Five financial metrics were used to compare these two companies' overtime. This included Total Revenues, Gross Profit, EBIT, Net Debt, and Full Time Employees. Additionally, for these two companies, I determined the top 15 organizations that hold the most ownership for the past two years from 2021 to 2022. You can find this information in the _.html_ export.

A Pearson correlation was performed between the two firms' stock prices and trading volume, as well as an inventory study comparing the _**Days Inventory Outstanding**_ ratio, which measures the average number of days a company keeps inventory before selling it. The goal here was to determine if the firms had good or bad inventory management.

The presentation (.pptx) includes a full description of this analysis.

## How to Run code
In order to run the following source files in this project, RStudio and R will be needed.   

Links:  
[R](https://cran.r-project.org/bin/windows/base/)  
[RStudio](https://posit.co/products/open-source/rstudio/)
