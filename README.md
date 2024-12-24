# Food Order and Cooking Session Analysis

This repository contains the analysis of user behavior, cooking preferences, and order trends using three datasets: `UserDetails.csv`, `CookingSessions.csv`, and `OrderDetails.csv`.

## Project Overview

This project analyzed the relationship between cooking sessions, user demographics, and order patterns through data cleaning, merging, analysis, and visualization.

## Workflow

1.  **Data Merging:** Merged datasets based on `Session ID` and `User_ID`.
2.  **Data Preprocessing:** Removed redundant columns, filled missing values with 0, and saved to `DataAnalystIntern_merged.csv`.
3.  **Data Visualization:** Created visualizations including:
    *   Bubble Chart (Sessions vs. Orders)
    *   Bar Plot (Top 3 Dishes)
    *   Plots (Sessions/Orders by Age Group)
    *   Distribution Plot (Session Ratings)
    *   Pie Chart (Favorite Meals)
    *   Heatmap (Dish Popularity by Meal Type)
    *   Box Plot (Session Duration by Meal Type)
    *   Folium Map (Geographical Distribution with location details)

## Files

*   `DataAnalystIntern_merged.csv`: Merged and preprocessed data.
*   `ipynb file`: Analysis and visualization code.
*   `README.md`: This file.

## Libraries

*   pandas, NumPy, matplotlib, seaborn,Folium, geopy

## Conclusion

This analysis provides insights into user cooking and ordering behavior for potential business applications.
