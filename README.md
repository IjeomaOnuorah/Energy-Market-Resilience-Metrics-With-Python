# Energy Market Resilience Metrics: Analyzing Vulnerabilities and Preparing for Disruptions
## Table Of Contents
- [Overview](#overview)
- [Features](#features)
- [Files](#files)
- [Dataset Overview](#dataset-overview)
- [Getting started](#getting-started)
- [Instructions](#instructions)
- [Data Preprocessing](#data-preprocessing)
- [Dependencies](#dependencies)
- [Sample Visualizations](#sample-visualizations)
- [Recommendations](#recommendations)
- [Data Source](#data-source)
- [Contact](#contact)

## Overview
This project focuses on analyzing the resilience of energy markets using historical, infrastructure, and market datasets. The goal is to identify trends and factors affecting market stability and provide actionable insights for stakeholders.

## Features
- Cleaning and preprocessing data.
- Exploratory data analysis(EDA)
- Visualization energy trends, demand, and market behavior.
- Insights/Recommendations on infrastructure challenges and market dynamics.

## Files
Energy-Market-Resilience
- **Data**: historical_energy_data.csv, infrastructure_data.csv, market_data.csv and regulatory_data.csv
- **Notebooks**: Energy_Market_Resilience_Metrics.ipynb
- **README.md**

Click 🧨[here](https://drive.google.com/drive/folders/1yMs4UH3Kumu37IvgNrSh22oNssTzGIft?usp=sharing)🧨 to see these files

## Dataset Overview
1. Historical Energy Data
  - Fields: Energy demand, consumption, price, production.
  - Purpose: Analyze historical trends in energy usage and pricing.
2. Infrastructure Data
  - Fields: Maintenance records, infrastructure status, technology limitations.
  - Purpose: Assess the state of energy infrastructure and its impact.
3. Market Data
  - Fields: Market price, competitor data, demand trends.
  - Purpose: Understand market dynamics and competitive positioning.
4. Regulatory Data
  - Fields: Regulatory changes, compliance status and compliance costs
  - Purpose: Assess impact of regulatory changes and compliance costs

## Getting Started
Ensure you have the following installed:
- Python (>= 3.8)
- Jupyter Notebook

## Instructions
1. Clone or download this repository to your local machine.
2. Navigate to the project directory.
3. Installation of dependencies
4. Launch Jupyter Notebook
5. Open the file notebooks/Energy_Market_Resilience_Metrics.ipynb to start the analysis.

##  Data Preprocessing
- **Data Cleaning**:
  - Checked for and handled missing values, data types and duplicate rows.
  - Standardized column names for consistency across datasets.
- **Data Transformation**:
  - Converted date columns to datetime format.
  - Normalized numerical columns to bring all values into a similar scale for analysis.
 
## Dependencies
```Python
#importation of dependencies
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
```

## Sample Visualizations
### 1. Energy Demand, Production and Consumption Trends
This line chart shows the trends in energy demand, production and consumption over time, highlighting seasonal spikes and long-term trends.
![Energy Demand Trends](https://github.com/user-attachments/assets/847fe366-5da1-4212-a0f7-7f181a1bf0f8)

### 2. Market Price vs Energy Price
A visualization showing the relationship between market price and Energy Price, providing insights into market volatility.  
![Market price 2](https://github.com/user-attachments/assets/233c9e66-2785-440b-b3ab-50a89c6cc486)

### 3. Infrastructure Maintenance Frequency 
A barchart showing the frequency of various Infrastructure Status values and the distribution of Technology Limitations
![Infrastructure staure 3](https://github.com/user-attachments/assets/0d6f698b-ac21-4b22-9b3d-1afba0d39de2)

### 4. Impact of Regulatory Changes and Operational Costs on Revenue
A lineplot showing the relationship between regulatory changes and the associated compliance costs, as well as the operational costs to the Revenue generated from the company.

This provides insights into the financial implications of regulatory changes cost and operational cost for Energix Enterprise.
![Image 6](https://github.com/user-attachments/assets/02d18971-6a68-441f-b781-d487e81648fb)

### 5. Analyzing Competition from Renewable Energy Providers
A linechart demostrating the trends in energy production based on the energy source (Fossil Fuels vs. Renewables) over time. This gave us insights into how the production from renewables has evolved and potentially affected the company's market share.
![Image 7](https://github.com/user-attachments/assets/72ba2073-dfad-4685-819d-197f7541b8ed)

## Recommendations
1. Energix Enterprise should consider diversifying its energy production portfolio to mitigate the risks associated with fluctuations in demand and production.
2. Given that energy price doesn't correlate with energy demand, Energix should consider implementing a dynamic pricing model. This model can adjust prices based on demand, production costs, and other market factors. Such a model can help in improving sales during high-demand periods and maintaining profitability during low-demand times.
3.  With most of the company's infrastructure in 'Poor' status and high technology limitations, Energix should prioritize investments in infrastructure upgrades.
4.  With most of the company's infrastructure in 'Poor' status and high technology limitations, Energix should prioritize investments in infrastructure upgrades.
5.  Conduct regular market research to understand consumer preferences, especially concerning renewable energy. This can guide Energix's strategy in terms of energy source diversification and pricing.

## Data Source
The datasets was obtained from Amdari.io and includes 4 different datasets: historical, market, infrastructure and regulatory data.

## Contact
For inquiries or collaborations, feel free to reach out:
- [LinkedIn](www.linkedin.com/in/ijeomaonuorah)
- Email: c.onuorahijeoma@gmail.com






