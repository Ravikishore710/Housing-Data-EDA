# 🏡 California Housing Data Analysis & Preprocessing

This project presents a detailed exploration and preprocessing of the California housing dataset. The workflow includes exploratory data analysis (EDA), visualization, and preparation of features for machine learning tasks.

---

## 📌 Objective

- Understand the distribution and characteristics of housing data.
- Identify relationships and trends across features.
- Prepare the data through imputation, normalization, and encoding.
- Create a clean and ready-to-use dataset for modeling tasks.

---

## 📥 Dataset Overview

The dataset includes information such as:
- Housing median age  
- Total rooms and bedrooms  
- Population and households  
- Median income and house value  
- Ocean proximity (categorical location feature)  
- Latitude and longitude  

This diverse mix of numerical and categorical data provides a strong foundation for geographic and demographic analysis.

---

## 🔍 Initial Exploration

The dataset was inspected to:
- Understand data types
- Detect missing values
- Review statistical summaries
- Examine category distributions (e.g., ocean proximity)

These steps help ensure data quality and identify preprocessing needs early on.

---

## 📊 Visual Explorations

Several visualizations were used to uncover patterns and correlations:

### 1. Pairplot by Ocean Proximity
Revealed how income, housing age, and house value vary by region.

### 2. Feature-wise Scatter Plots
Visualized each numeric feature over the data index to spot trends and outliers.

### 3. Joint Distribution: Total Rooms vs Total Bedrooms
Analyzed multicollinearity between room-related features.

### 4. Count Plot: Ocean Proximity
Showed distribution of data points across coastal and inland regions.

### 5. Population vs Households
Helped assess population density and urban planning structure.

### 6. Median Income Distribution by Region
Plotted ridgelines showing how income levels shift based on proximity to the ocean.

---

## 🧹 Data Preprocessing Pipeline

### 🔢 Numeric Features
- Missing values were imputed using the **median strategy**.
- Features were scaled using **MinMaxScaler** for normalized model input.

### 🅰️ Categorical Features
- Missing values were filled with the **most frequent category**.
- Categories were encoded using **custom label mappings** for model interpretability.

---

## 🧩 Feature Integration

After transformation:
- All processed numerical and categorical features were merged into a final dataset.
- Latitude, longitude, and target (`median_house_value`) were preserved for spatial and supervised learning use.

---

## ✅ Outcome

A clean, normalized, and fully encoded dataset — ready for regression modeling, clustering, or geospatial analysis.

---

## 📌 Next Steps

- Build predictive models to estimate house value.
- Explore geographic segmentation or clustering.
- Integrate external data sources (e.g., economic zones, school districts) for enhanced modeling.

---
