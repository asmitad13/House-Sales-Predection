# House Sales in King County, Washington

## Overview

This project analyzes housing sales data in King County, Washington, using Tableau to build dynamic dashboards and uncover key insights about the housing market. The goal is to showcase advanced data visualization skills and derive actionable insights from the dataset.

## Dataset

- **Name:** King County Housing Sales Dataset
- **Description:** The dataset includes details about houses sold in King County, Washington, between May 2014 and May 2015. It contains information such as the price, number of bedrooms and bathrooms, living area, lot size, year built, renovation details, and location (latitude and longitude).

## Objectives

1. Understand the trends and factors influencing house prices in King County.
2. Visualize relationships between features like square footage, location, and pricing.
3. Build interactive Tableau dashboards to present data insights effectively.

## Steps Involved

### 1. Data Preprocessing
- **Tool Used:** Python
- **Steps:**
  - Cleaned and formatted the dataset (e.g., converted date columns to the appropriate format).
  - Checked for missing or null values and handled them as required.
  - Generated additional calculated fields for better analysis, such as `Price per Sqft`.

### 2. Data Import into Tableau
- Imported the preprocessed dataset into Tableau for visualization.

### 3. Building Dashboards in Tableau
- **Key Dashboards:**
  1. **Price Distribution Dashboard:**
     - Histogram of house prices.
     - Highlighted price ranges using filters and color-coded zones.
  2. **Geographic Distribution of Sales:**
     - Map visualization showing house sales by location.
     - Added layers for average price per zip code.
  3. **Price vs. Features Analysis:**
     - Scatter plots showing the relationship between price and square footage, number of bedrooms, and other features.
     - Interactive filters for selecting ranges.
  4. **Time Series Analysis:**
     - Line chart showing the trend of house sales over time.
     - Integrated time-based filters.

### 4. Insights from Visualizations
- **High-Value Areas:** Waterfront properties and those with better views command significantly higher prices.
- **Renovations Impact:** Renovated homes tend to have higher prices compared to similar non-renovated properties.
- **Price Drivers:** Square footage and location (proximity to desirable neighborhoods) are major price determinants.
- **Temporal Trends:** Peak sales observed in certain months, indicating seasonality.

# Dashboard 

<img width="1468" alt="Screenshot 2024-12-31 at 10 00 31 AM" src="https://github.com/user-attachments/assets/4602c6bb-58f2-4744-8439-eae29be7428f" />

## Tools and Technologies

- **Data Cleaning:** Python (pandas, numpy)
- **Visualization:** Tableau
- **Other Tools:** Jupyter Notebook for preprocessing and exploratory data analysis

# Challenges
- Handling missing data in key features such as yr_renovated.
- Ensuring geographical data alignment for map-based visualizations.
- Balancing performance with high data granularity in Tableau.

# Future Work
- Include predictions for house prices using regression models in Python or Tableau’s built-in forecast functionality.
- Enhance dashboards with advanced filters and calculated KPIs.
- Explore other related datasets to include demographics or economic indicators for deeper analysis
