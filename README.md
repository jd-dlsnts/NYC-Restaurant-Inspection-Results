NYC Restaurant Inspection Analysis

Overview
This project analyzes over 290,000 restaurant inspection records from New York City's five boroughs, sourced from NYC Open Data. Using SQL, the analysis examines inspection types, grade distributions, common violation categories, and borough-level compliance patterns to surface actionable insights for restaurant owners and aspiring business owners in New York City.
Tools Used
SQL (DB Browser for SQLite)

Dataset
DOHMH New York City Restaurant Inspection Results
Source: NYC Open Data — [Download here](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j)
Records: 290,000+
Coverage: All five NYC boroughs

Files in this Repository

nyc_restaurant_inspections.csv — raw dataset from NYC Open Data
nyc_restaurant_analysis.sql — all SQL queries used in this analysis
nyc_restaurant_findings.pdf — written findings and recommendations

Key Findings

Only 67.54% of graded inspections result in an A grade, below what should be expected for establishments serving food for human consumption
Cleanliness and pest-related violations account for roughly 28% of all citywide violations, the most preventable category
The Bronx leads all boroughs in pest violation rate despite having a smaller sample size than Brooklyn, Queens, and Manhattan
Certain cuisine types including Creole, Bangladeshi, and Pakistani carry significantly higher B and C grade rates relative to their inspection volume

Intended Audience
Restaurant owners and aspiring business owners in New York City looking to understand compliance patterns before and during operations.
