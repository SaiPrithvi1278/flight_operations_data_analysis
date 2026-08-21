# Day 10 — Flight Operations Data Analysis

## Overview

This project analyzes a Flight Operations dataset using **Python and Pandas**. The notebook follows a complete data-analysis workflow: loading and understanding the data, checking data quality, selecting and filtering records, sorting, grouping and aggregation, creating useful transformations, and drawing observations.

## Objectives

- Load and inspect the Flight Operations dataset.
- Check data types, missing values, and duplicate records.
- Select and filter useful flight records.
- Sort flights using operational and financial metrics.
- Group data by airline, flight status, travel class, weather, booking channel, origin, and destination.
- Create derived columns such as occupancy rate, estimated revenue, month, day of week, and delay category.
- Identify patterns and write key observations.

## Dataset

The dataset contains **180 flight records** and **17 original columns**, including airline, origin, destination, aircraft, travel class, passengers, seat capacity, ticket price, delay, flight status, weather, booking channel, baggage, meal preference, and passenger satisfaction.

## Pandas Concepts Used

`read_csv()` • `head()` • `shape` • `info()` • `describe()` • `isnull()` • `duplicated()` • column selection • boolean filtering • `sort_values()` • `groupby()` • `agg()` • `fillna()` • datetime operations • derived columns • conditional transformations

## Key Findings

- Vistara has the highest estimated revenue in the provided sample.
- On-time flights form the largest flight-status category.
- Delayed flights have substantially higher average delays and lower passenger satisfaction than on-time flights.
- Economy class contributes the largest passenger volume and total estimated revenue.
- Premium Economy has the highest average passenger satisfaction among the travel classes.
- Delhi is the busiest origin by passenger volume.
- Storm conditions show a relatively high delayed-flight rate in the sample.
- Some flights have passenger counts above recorded seat capacity, creating occupancy rates above 100%; this should be investigated as a data-quality issue.

## Files

- `Day10_Flight_Operations_Analysis.ipynb` — Complete Google Colab/Pandas analysis notebook.
- `Day10_Flight_Operations_Dataset.csv` — Flight Operations dataset.

## How to Run

1. Open the `.ipynb` file in **Google Colab**.
2. Upload `Day10_Flight_Operations_Dataset.csv` when prompted if it is not already available.
3. Run the notebook cells from top to bottom.
4. Review the analysis tables and observations.
5. Upload the notebook and dataset to GitHub.

## Note

The observations are based only on the supplied dataset and describe patterns in this sample.
