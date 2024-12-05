# Energy Market Resilience Metrics: Analyzing Vulnerabilities and Preparing for Disruptions
## Overview
This project focuses on analyzing the resilience of energy markets using historical, infrastructure, and market datasets. The goal is to identify trends and factors affecting market stability and provide actionable insights for stakeholders.

## Features
- Cleaning and preprocessing data.
- Visualizing energy trends, demand, and market behavior.
- Drawing insights into infrastructure challenges and market dynamics.

## Files
Energy-Market-Resilience
- **Data**: historical_energy_data.csv, infrastructure_data.csv, market_data.csv and regulatory_data.csv
- **Notebooks**: Energy_Market_Resilience_Metrics.ipynb
- **README.md**
- **requirements.txt**

Click 🧨[here](https://drive.google.com/drive/folders/1yMs4UH3Kumu37IvgNrSh22oNssTzGIft?usp=sharing)🧨 to see these files

## Datasets
1. Historical Energy Data
  - Fields: Energy demand, consumption, price, production.
  - Purpose: Analyze historical trends in energy usage and pricing.
2. Infrastructure Data
  - Fields: Maintenance records, infrastructure status, technology limitations.
  - Purpose: Assess the state of energy infrastructure and its impact.
3. Market Data
  - Fields: Market price, competitor data, demand trends.
  - Purpose: Understand market dynamics and competitive positioning.

## Getting Started
Ensure you have the following installed:
- Python (>= 3.8)
- Jupyter Notebook

##  Data Preprocessing
- **Data Cleaning**:
Handled missing values using mean/median imputation or dropping incomplete rows.
Standardized column names for consistency across datasets.
- **Data Transformation**:
Converted date columns to datetime format.
Normalized numerical columns to bring all values into a similar scale for analysis.
- **Outlier Detection**:
Identified outliers using the Z-score and IQR methods.
Filtered or flagged anomalous entries for further investigation.

## Sample Visualizations
### 1. Energy Demand, Production and Consumption Trends
This line chart shows the trends in energy demand, production and consumption over time, highlighting seasonal spikes and long-term trends.
![Energy Demand Trends](https://drive.google.com/file/d/1aAHBalKz5l4yVprZexfDSa4WmmOGk7Wm/view?usp=sharing)
### 2. Market Price vs Energy Price
A visualization showing the relationship between market price and Energy Price, providing insights into market volatility.  
![Market Price vs Demand](visualizations/market_price_vs_demand.png)
### 3. Infrastructure Maintenance Frequency 
A barchart showing the frequency of various Infrastructure Status values and the distribution of Technology Limitations
![Infrastructure Maintenance](visualizations/infrastructure_maintenance.png)
### 4. Relationship between Infrastructure Status and Technology Limitations
A heatmap showing the relationship between various Infrastructure Status and the distribution of Technology Limitations
![Infrastructure Maintenance](visualizations/infrastructure_maintenance.png)
### 5. Regulatory Changes and Compliance Costs
A barchart and histogram showing the frequency of various Regulatory Changes and the distribution of Compliance Costs associated with these change
![Infrastructure Maintenance](visualizations/infrastructure_maintenance.png)
### 6. Impact of Regulatory Changes and Operational Costs on Revenue
A lineplot showing the relationship between regulatory changes and the associated compliance costs, as well as the operational costs to the Revenue generated from the company.

This provides insights into the financial implications of regulatory changes cost and operational cost for Energix Enterprise.
![Infrastructure Maintenance](visualizations/infrastructure_maintenance.png)
### 7. Analyzing Competition from Renewable Energy Providers
A linechart demostrating the trends in energy production based on the energy source (Fossil Fuels vs. Renewables) over time. This gave us insights into how the production from renewables has evolved and potentially affected the company's market share.
![Infrastructure Maintenance](visualizations/infrastructure_maintenance.png)

