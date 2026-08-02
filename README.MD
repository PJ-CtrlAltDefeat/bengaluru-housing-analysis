# Bengaluru Housing Market Analysis

Data cleaning, anomaly detection, and price analysis on 13,000+ real Bengaluru property listings, using Python (pandas, matplotlib).

## What this project does
- Cleans a messy real-world dataset: handles missing values, extracts bedroom counts from inconsistent text, converts range-based square footage into usable numbers
- Flags anomalous listings using two methods: a real-estate business rule (implausible sqft-per-bedroom ratios) and location-aware statistical outlier detection (IQR method)
- Quantifies price-per-square-foot trends across Bengaluru's highest-volume neighborhoods

## Key findings
- Identified 951 anomalous listings (7.2% of the dataset)
- Found a 391% price-per-sqft spread between the cheapest and priciest high-volume locations
- Indira Nagar, Malleshwaram, and Rajaji Nagar emerged as the highest-cost micro-markets; Chandapura and Electronic City Phase II as the most affordable high-volume areas

## Tools
Python, pandas, matplotlib, Google Colab

## Data source
[Bengaluru House Price dataset](https://github.com/johnjoel2001/Bangalore_house_price_prediction), originally sourced from Kaggle
