Transport Trends Analysis
Exploring Long-Term Vehicle Registration and Mobility Patterns
Project Overview

This project explores long-term transport data to understand how vehicle registrations and licensing activity have evolved over time. The dataset contains historical records of vehicle registrations and licensed vehicles, segmented by transport categories and vehicle types.

The goal is to extract meaningful business insights that can support transport policy decisions, infrastructure planning and market opportunity analysis.

Objectives
Analyze long-term transport activity trends
Identify dominant transport categories
Compare new vehicle registrations vs existing licensed vehicles
Explore how transport activity changes over time
Generate actionable insights for decision-making

Dataset Description

The dataset contains 45,000+ records and includes the following key variables:

Period → Time of observation (year/month)
Data_value → Number of vehicles or transport activity measure
Group → Main transport system category
Series_title_1 → Vehicle type classification
Series_title_2–5 → Detailed breakdowns (engine size, weight class, usage type)
UNITS → Measurement unit
STATUS → Data quality indicator

Data Cleaning Process

Key preprocessing steps included:

Removed irrelevant or empty columns (Series_title_3–5, Suppressed)
Handled missing values in Data_value
Converted Period into a usable Year feature
Standardized dataset for time-series and categorical analysis

Exploratory Data Analysis (EDA)

The analysis was structured into three levels:

Univariate Analysis
Distribution of transport activity values
Frequency of transport categories
Observation distribution over time
Bivariate Analysis
Transport activity trends over time
Contribution of each transport category to total activity
Multivariate Analysis
Evolution of transport categories over time
Comparison of multiple transport systems across years
Key Insights
Transport activity is heavily concentrated in a small number of categories.
Vehicle licensing (existing fleet) dominates over new vehicle registrations.
Transport activity shows long-term growth with fluctuations across periods.
Different transport categories evolve at different rates over time.
The transport system is driven more by fleet size (stock) than new vehicle inflows (flow).

Business Implications
Transport Policy

Focus should be placed on managing dominant vehicle categories that contribute most to system load.

Infrastructure Planning

Long-term growth in licensed vehicles suggests increasing pressure on roads and urban transport systems.

Market Opportunities

Emerging or growing vehicle categories may represent opportunities for manufacturers and service providers.

Tools & Technologies
Python 
Pandas
NumPy
Matplotlib
Seaborn
Jupyter / Kaggle Notebooks
Project Structure
transport-trends-analysis
 ├── data/
 ├── notebook/
 ├── README.md
Future Improvements
Add forecasting models for transport demand
Break down analysis by fuel type (if available)
Build interactive dashboard (Power BI or Plotly)
Integrate regional transport comparisons
👤 Author

Tawanda Colina Tsayang
Business Intelligence & Data Analytics Student
Focused on Data-Driven Strategy, AI, and Decision Intelligence
