# Boutique Winery Customer Targeting Analytics

Customer analytics project using RFM segmentation, logistic regression, and lift analysis to help a boutique winery prioritize high-value customer outreach.

## Business Question

How can the winery better target customers across segments, regions, and marketing channels to unlock greater customer value?

## Project Overview

The dataset included 65,534 sales records from 22,869 unique customers across 2008–2010. It included customer segments, transaction history, sales channels, subscription status, and geographic information.

The analysis focused on:

- RFM customer segmentation
- Winemaker Call targeting using logistic regression
- Churn analysis
- Customer lifetime value and multi-channel engagement

## My Main Contribution

My primary contribution was building the Winemaker Call targeting model.

Winemaker Calls were a valuable sales channel, but calling capacity was limited. I built a customer-level logistic regression model using 2008–2009 customer behavior to predict which customers were most likely to make a Winemaker Call purchase in 2010.

## Key Results

- Built a logistic regression model with an AUC of 0.845.
- The top 10% of customers ranked by model score captured 50.4% of future Winemaker Call buyers.
- The top 20% captured 70.6% of future Winemaker Call buyers.
- Estimated a $44.62 customer lifetime value premium associated with multi-channel engagement.

## Tools Used

Python, Pandas, NumPy, scikit-learn, Logistic Regression, Tableau, Google Colab

## Project Files

- [Modeling Notebook](notebooks/winemaker_call_targeting.ipynb)
- [Final Report](reports/customer_analytics_final_report.pdf)
- [Presentation](reports/winery_customer_analytics_presentation.pdf)

## Note on Data

The original dataset is not included because it was provided for academic use.
