Individual Finance Analysis (R)
Overview

This project analyzes personal income and expense data from 2022 to understand spending behavior, income patterns, and category-level financial trends. Using R, I cleaned raw transaction data, performed exploratory analysis, and produced visualizations that highlight variability in monthly cash flow and spending distribution.

Objectives

Clean and structure raw financial transaction data

Compare income versus expense patterns over time

Identify high-variance spending categories

Generate clear, reproducible visualizations for personal finance insights

Data

The dataset consists of anonymized personal financial transactions, including:

Date and time of transaction

Category (e.g., food, transportation, household)

Income vs. expense classification

Transaction amount and currency

Missing values and irrelevant fields were removed to improve analytical accuracy.

Methods

Data Cleaning & Transformation:
Used dplyr, tidyr, and lubridate to clean dates, remove null values, and standardize variables.

Exploratory Data Analysis:
Generated summary statistics and filtered monthly transactions to analyze recurring financial behavior.

Visualization:
Built scatter plots, boxplots, and faceted bar charts with ggplot2 to compare income and expense distributions across time and categories.

Interactivity (Optional):
Converted selected visualizations to interactive plots using plotly.

Key Visualizations

Monthly income vs. expenses by amount

Distribution of income and expense transactions

Spending patterns by category

These visuals reveal irregular income timing, consistent low-level spending, and a small number of high-impact expense categories.

Tools & Libraries

R

tidyverse (dplyr, tidyr, ggplot2)

plotly

lubridate

Outcomes

This analysis demonstrates how exploratory data analysis can be applied to personal finance data to surface spending patterns, income variability, and financial risk points. The project emphasizes reproducible workflows and clear data storytelling.

