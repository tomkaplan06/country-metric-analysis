# country-metric-analysis

Metrics Analysis Across 200+ Territories

Overview

This project analyzes various metrics collected from over 200 territories to understand patterns and relationships between these metrics. Using statistical methods, particularly correlation analysis, we identify key trends and insights that can inform decision-making and further research.

Data

The dataset includes metrics such as Purchasing Power Value, Safety Value, Health Care Value, Cost of Living Value and Quality of Life Value.

Data covers more than 200 distinct territories.

Sources: https://www.kaggle.com/datasets/ahmedmohamed2003/quality-of-life-for-each-country

Objectives

- Explore the distribution of different metrics across territories.
- Investigate correlations and relationships between metrics.
- Identify significant positive and negative correlations.
- Provide visualizations to illustrate key findings.

Methods

- I used the pandas module to import the dataset and clean the data by removing the rows with missing/incomplete information
- Leveraged the stats module from SciPy to create linear regression models and calculate the correlation coefficient for each plot I made

Key Findings

- There is a very strong positive correlation between the Purchasing Power Index and the Quality of Life Index, indicating that territories with higher purchasing power tend to also have a higher quality of life.
- Weak positive correlation between Cost of Living Value and Safety Value, indicating that countries with a higher cost of living tend to be safe but it is not a large factor
- Strong negative correlation between Property Price to Income Value and Quality of Life Index, meaning that highly developed countries tend to have a lower Property Price to Income ratio.

How to Use

The Jupyter notebook (metricanalysis.ipynb) contains all the code for data loading, cleaning, analysis, and visualization.

To reproduce the analysis, clone this repo and run the notebook.

Dependencies: Python 3 (ipykernel), pandas, numpy, matplotlib, scipy
