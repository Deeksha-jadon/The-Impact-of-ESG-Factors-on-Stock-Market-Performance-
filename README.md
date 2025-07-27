# The-Impact-of-ESG-Factors-on-Stock-Market-Performance.
# Library Imports

**import pandas as pd**(Used for data manipulation and analysis)

**import numpy as np**(Fundamental package for numerical computations)

**import matplotlib.pyplot as plt**(Used for creating static visualizations (line plots, bar charts, etc.))

**import seaborn as sns**(Advanced visualization library built on top of matplotlib like aesthetics, complex plots)

**from sklearn.linear_model import LinearRegression**(For applying linear regression models to examine relationships between variables)

**from sklearn.cluster import KMeans**(For performing clustering analysis)

**from sklearn.preprocessing import StandardScaler**(For standardizing/scaling numerical features before modeling)

**Project Objective**
To investigate whether Environmental, Social, and Governance (ESG) risk scores can impact annual stock returns (2020–2024) of Nifty 50 companies, and to uncover deeper patterns using regression, clustering, and sectoral analyses.

**Project Description**
This quantitative study uses secondary data (ESG scores from Sustainalytics/Refinitiv/MSCI and annual returns from NSE) for 2020–2024. Key steps:

**Data Preparation**
Import ESG risk scores, risk levels, sector labels, and annual return (%)
Clean and merge datasets into a single DataFrame

**Descriptive Statistics**
Summary metrics (mean, median, SD, min/max) for ESG scores and returns across years

**Correlation & Regression**
Pearson correlation (r ranging from –0.14 to +0.30)
Simple linear regression plots with confidence intervals
Clustering (KMeans)

**Group companies into three clusters based on 2024 ESG scores and returns**
Visualize and interpret cluster profiles

**Sectoral Analysis**
Bar charts of average annual returns by sector
Company count and ESG distribution per sector

**Key Findings**
Weak/Inconsistent Correlation
ESG risk scores alone show no reliable linear relationship with returns (r near zero most years).

Regression Analysis
Flat or shallow slopes and wide confidence bands confirm poor predictive power of ESG risk on returns.

Behavioral Clusters

Cluster 0: Low ESG risk, high returns (core ESG‑aligned performers)
Cluster 1: High ESG risk, mixed returns (high‑risk/high‑reward cases)
Cluster 2: Moderate ESG risk, low/negative returns (underperformers)

Sector Context Matters
Communication Services and Technology led in 2024 returns regardless of ESG risk; sectors like Basic Materials lagged.

**Conclusion**
ESG risk scores alone are not sufficient to predict short‑term stock performance.

Multi‑factor approaches (combining ESG with financial ratios and sector benchmarks) and behavioral segmentation offer stronger investment insights.

**Recommendations**
Combine ESG with financial metrics (P/E, revenue growth) for screening.

Use clustering to segment portfolios by risk–return behavior.

Incorporate sectoral benchmarks to contextualize ESG impact.

Extend analysis with additional features (market cap, volatility) for richer modeling.


