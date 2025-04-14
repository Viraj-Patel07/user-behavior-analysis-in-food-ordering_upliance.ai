# 🍽️ Food Order and Cooking Session Analysis

This repository contains the analysis of user behavior, cooking preferences, and order trends using three datasets: `UserDetails.csv`, `CookingSessions.csv`, and `OrderDetails.csv`.

---

## 📌 Project Overview

This project explores the relationship between cooking sessions, user demographics, and order patterns through data cleaning, merging, analysis, and insightful visualizations.

---

## 🔄 Workflow

### 1. 🔗 Data Merging
- Combined datasets using `Session_ID` and `User_ID` to create a unified view.

### 2. 🧹 Data Preprocessing
- Removed redundant columns
- Filled missing values with `0`
- Exported cleaned data to `DataAnalystIntern_merged.csv`

### 3. 📊 Data Visualization
Created various visualizations to extract key patterns and insights:
- 🫧 **Bubble Chart** – Sessions vs. Orders
- 📊 **Bar Plot** – Top 3 Most Ordered Dishes
- 👥 **Grouped Plots** – Sessions/Orders by Age Group
- 📈 **Distribution Plot** – Session Ratings
- 🥧 **Pie Chart** – Favorite Meal Types
- 🔥 **Heatmap** – Dish Popularity by Meal Type
- 📦 **Box Plot** – Session Duration by Meal Type
- 🗺️ **Folium Map** – Geographic Distribution of Users/Cooking Sessions

---


## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `folium`
- `geopy`

---

## 💡 Conclusion

This analysis provides meaningful insights into user behavior, cooking preferences, and ordering patterns. It can be leveraged for:

- Enhancing user experience through personalization
- Optimizing meal offerings based on popularity
- Strategic business decisions using data-driven trends

---


