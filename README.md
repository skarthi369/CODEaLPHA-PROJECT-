project 1
# A/B Testing for Marketing Campaign Optimization

This project analyzes the performance of two marketing campaigns, a control campaign and a test campaign, using A/B testing methodology. The goal is to determine if the test campaign leads to statistically significant improvements in key performance indicators (KPIs) compared to the control campaign. 

## Data

The project utilizes two datasets containing information on campaign performance metrics such as impressions, clicks, purchases, and spend. The data is processed and cleaned using Python libraries like Pandas and NumPy.

## Methodology

1. **Data Exploration and Visualization:** The data is explored using descriptive statistics and visualizations such as KDE plots and box plots to understand the distributions of key metrics and identify potential outliers.

2. **KPI Calculation:** Relevant KPIs such as Click-Through Rate (CTR), Conversion Rate (CR), Cost-Per-Click (CPC), and Cost-Per-Acquisition (CPA) are calculated to evaluate campaign effectiveness.

3. **Statistical Testing:** The Mann-Whitney U test is applied to compare the distributions of KPIs between the control and test campaigns. This non-parametric test is used due to the non-normality of the data.

4. **Results and Insights:** The results of the statistical tests are interpreted to identify any significant differences in campaign performance. These insights provide recommendations for campaign optimization.

## Tools and Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn, Pingouin, Statsmodels, Google Colab.

## Outcome

The project aims to determine whether the test campaign is more effective than the control campaign based on the chosen KPIs. It provides data-driven insights for improving marketing strategies and maximizing return on investment.
