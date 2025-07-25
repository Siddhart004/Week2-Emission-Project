📘 Week 2 – Emission Analysis of U.S. Supply Chain Data (2010–2016)
This Jupyter Notebook performs a comprehensive analysis of U.S. supply chain emission factors using data from 2010 to 2016, sourced from a multi-sheet Excel file. The analysis includes data cleaning, merging, preprocessing, and scaling in preparation for machine learning tasks like regression.

📂 Dataset Overview
Source: SupplyChainEmissionFactorsforUSIndustriesCommodities.xlsx

Sheets:

{year}_Detail_Commodity

{year}_Detail_Industry

Years Covered: 2010 to 2016

Targets:

Supply Chain Emission Factors with Margins

Without Margins and Margins for comparison

🛠️ Key Steps Performed
Imported and combined data from multiple yearly sheets

Cleaned and standardized column names

Labeled Commodity and Industry sources

Handled missing values

Encoded categorical features (e.g., Substance, Unit)

Applied feature scaling (StandardScaler) for model readiness

Visualized target variable distribution using Seaborn

📊 Potential Applications
Emission factor prediction (regression)

Industry-wise environmental analysis

Time-series or trend analysis from 2010 to 2016

Feature importance exploration using tree-based models



