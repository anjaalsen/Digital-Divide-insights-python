# Digital-Divide-insights-python

## Project Overview
This project explores global internet adoption and its relationship with economic factors. Using Python for exploratory analysis and Tableau for visualization, the study identifies patterns in digital access, examines economic influences, and segments countries based on internet penetration and GDP.

## Data Source
The dataset consists of 20 individual datasets from the World Bank Open Data platform, accessed on 04.01.2025. It includes key global development indicators such as:
• Economic performance (GDP per capita),
• Demographics (population breakdown),
• Education (literacy rates, secondary education levels),
• Infrastructure (electricity access),
• Digital Access (internet users, broadband subscriptions)
This data spans multiple countries and regions over time, enabling longitudinal and comparative analysis.

In addition the following data was used: 
- GeoJSON Source: Core Geo Countries Dataset, provided by Natural Earth. Retrieved from [DataHub](https://datahub.io/core/geo-countries#data-files) on 04.01.2025.  
- This dataset is licensed under the Open Data Commons Public Domain Dedication and License (PDDL) v1.0. More details: [Open Data Commons PDDL](https://opendatacommons.org/licenses/pddl/1-0/).

## Research Questions
• How does GDP per capita influence internet adoption?
• What regional differences exist in digital access?
• Can economic indicators predict internet growth?
• How can countries be grouped based on digital access and economic factors?

## Analytical Approach
1. Exploratory Data Analysis (EDA)
Investigated internet usage patterns across regions Identified correlations between internet adoption and economic factors Created visualizations in Python to uncover trends
2. Statistical & Machine Learning Techniques
Linear Regression → Tested GDP’s role in internet adoption, confirming a positive relationship but with limitations Clustering Analysis (Unsupervised ML) → Grouped countries into four clusters based on GDP, internet users, and education Time Series Analysis → Examined trends in internet adoption over time, revealing a gradual increase with a plateau effect

## Key Findings
• GDP & Internet Access → Higher GDP generally leads to increased internet penetration, but exceptions exist due to policy, infrastructure, and market differences.
• Clustering Insights → Countries fall into four digital access groups, highlighting economic and regional disparities.
• Limitations → GDP per capita does not fully explain internet adoption—factors like policy frameworks, infrastructure, and urban-rural divides play a role.

## Data Cleaning Procedures
• Merged 20 World Bank datasets
• Standardized country names and codes
• Handled missing values through interpolation & regional imputation
• Normalized economic and internet adoption metrics
• Filtered outliers and inconsistencies

## Tableau Dashboard
The final results are presented in an interactive Tableau dashboard, offering a structured view of digital access trends, economic influences, and clustering results. View the Tableau Dashboard (https://public.tableau.com/app/profile/anja.alsen/viz/250210_Ex6_7_Story/Story1?publish=yes)

This repository contains:
	• Python scripts for data cleaning, EDA, regression, clustering, and time-series analysis
	• Tableau workbook for data visualization
This project offers a data-driven foundation for understanding and addressing global digital inequality.

