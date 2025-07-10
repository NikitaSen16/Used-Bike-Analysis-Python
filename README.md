# 🏍️ Used Bike Price Analysis 
This project explores a dataset of used bikes to perform data cleaning, exploratory data analysis (EDA), 
and feature engineering with the goal of uncovering patterns and factors that influence resale prices.

---

## 📌 Project Objective

- Clean and preprocess raw used-bike data
- Analyze pricing trends based on model, location, mileage, and ownership
- Engineer new features like bike age and mileage category
- Generate insights that help understand what affects second-hand bike pricing

---

## 🧰 Tools & Technologies

- **Language**: Python  
- **Libraries**: Pandas, NumPy, Seaborn, Matplotlib  
- **Jupyter Notebook**

---

## 🧹 Data Cleaning & Preprocessing

- Extracted numeric values from `mileage`, `power`, and `kms_driven`
- Removed rows with missing locations
- Converted column types to appropriate numeric formats
- Cleaned inconsistent formatting in string columns

---

## 📊 Univariate Analysis

- Histogram for `price` distribution
- Pie chart showing share of different owner types
- Bar plots for top locations and most common model years

---

## 🔄 Multivariate Analysis

- Correlation heatmap of numerical features
- Scatter plots for `price` vs. `power`, `mileage`, and `kms_driven`
- Boxplots to compare price variations by `owner` and `location`
- Faceted scatter plots by ownership type

---

## 🏗️ Feature Engineering

- Created `bike_age` = Current Year - `model_year`
- Created `mileage_class` = Low / Medium / High buckets
- Extracted `brand` from `model_name` for grouped insights

---

## 📚 Grouped Analysis

- Top 5 models by average price
- Most fuel-efficient models on average
- Average price by owner type and location
- Top 10 models by resale value shown with a bar chart

---

## 🔍 Key Insights

- First-owner bikes tend to have higher resale value
- Power and mileage are moderately correlated with price
- Some cities have a higher concentration of premium bike listings
- Bikes with low mileage and newer age tend to be priced higher

---
