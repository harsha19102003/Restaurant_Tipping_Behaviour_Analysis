# Restaurant Tipping Behavior Analysis

This project performs an exploratory and statistical analysis of restaurant tipping behavior using the Seaborn *Tips* dataset. The objective is to investigate how variables such as total bill amount, customer gender, smoker status, and day of the week influence tipping patterns.

## Methodology

The analysis follows a standard data science workflow:

1. **Data Loading**

   * Dataset imported from the Seaborn library.

2. **Data Wrangling**

   * Creation of a derived feature `tip_percent` representing the percentage of tip relative to the total bill.

3. **Exploratory Data Analysis (EDA)**

   * Distribution analysis using histograms.
   * Group comparisons using violin plots.
   * Multivariate relationships explored with pairplots.
   * Correlation analysis using heatmaps.

4. **Statistical Testing**

   * One-way ANOVA tests applied to evaluate differences in tip percentage across:

     * Gender groups
     * Smoker vs non-smoker groups
     * Days of the week

5. **Regression Modeling**

   * Linear regression implemented to model the relationship between `total_bill` and `tip`.
   * The model is used to estimate expected tip values based on bill size.

6. **Interactive Visualization**

   * Plotly visualizations used to analyze average tipping trends by day.

## Technologies Used

* Python
* pandas
* seaborn
* matplotlib
* plotly
* scipy
* scikit-learn

## Key Findings

The analysis identifies a strong positive relationship between total bill size and tip amount. Statistical tests reveal minor variations in tipping patterns across different customer groups and days.

## Repository Structure

```
restaurant_tipping_analysis.ipynb   # Main analysis notebook
README.md                           # Project documentation
```

## Dataset

The dataset used is the **Tips dataset** provided by the Seaborn visualization library, containing 244 observations of restaurant bills and tipping information.
