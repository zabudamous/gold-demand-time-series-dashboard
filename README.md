Global Gold Demand Time Series Analysis Dashboard
Overview:

This project analyzes global gold demand across major markets using quarterly time series data. The objective was to identify structural demand patterns, measure market stability, and evaluate within-year concentration trends using reproducible data preparation and an interactive analytical dashboard.

The workflow integrates statistical data transformation in R with interactive modeling and visualization in Power BI Desktop.

Analytical Questions:

This project investigates three core questions:

• Which countries exhibit the most stable or volatile gold demand?
• How does demand evolve over time across major markets?
• Which quarters of the year typically concentrate the highest and lowest demand?

Data Preparation:

Raw datasets were reshaped and standardized using R to produce a unified time series structure.

Key preparation steps:
• Converted wide quarterly tables into long time series format
• Constructed date indices for chronological ordering
• Engineered growth metrics (Quarter-over-Quarter change)
• Computed country-level demand variability
• Exported clean dataset for dashboard modeling

All transformation steps are fully reproducible.

Dashboard Features:

The Power BI dashboard enables user-driven exploration of demand behavior across countries.

Page 1 — Global and Country Demand Trends

• Interactive time series comparison across markets
• Volatility ranking based on dispersion of quarterly demand
• Dynamic country filtering

Page 2 — Demand Dynamics

• Quarter-to-quarter growth analysis
• Comparative market behavior across selected countries
• Structural demand movement over time

Page 3 — Within-Year Demand Structure

• Aggregated demand by quarter
• Identification of peak and low demand periods
• Seasonal concentration patterns across markets

Key Findings:

Demand is structurally stable rather than shock-driven
Gold demand fluctuates within bounded ranges across major markets, indicating gradual structural change rather than abrupt volatility.

Demand exhibits consistent intra-year concentration patterns
Aggregated quarterly analysis reveals recurring seasonal structure in demand distribution across markets.

Tools and Technologies:

• R (data cleaning and feature engineering)
• Power BI Desktop (data modeling and dashboard design)

Repository Contents:

• Power BI dashboard file (.pbix)
• Cleaned time series dataset
• R data preparation script
• Dashboard export (PDF)
• Documentation and screenshots

Author:

Zeina Abudamous
Data Analysis | Time Series | Statistical Modeling
