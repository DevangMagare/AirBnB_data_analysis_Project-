# AirBnB_data_analysis_Project-
AirBnB_data_analysis_Project 

## 📌 Project Overview
This project focuses on performing an end-to-end data analysis on an Airbnb dataset.  
The goal is to understand pricing trends, rating distributions, neighborhood patterns,  
property types, and identify key insights that help describe the Airbnb market.

The entire analysis is conducted in a Google Colab Notebook using Python, Pandas, NumPy, and Matplotlib.

---

## 🗂 Project Structure
- **AirBnB_data_analysis.ipynb** — Main notebook containing all analysis steps
- **airbnb_data.csv** — Dataset used for cleaning and analysis
- **plots/** — Folder that stores generated visualizations
- **README.md** — Project documentation

---

## 🧼 Data Cleaning & Preparation
The dataset was cleaned using the following steps:
- Removed rows with missing or invalid values
- Processed the `rating` column by removing "No rating"
- Converted ratings to numeric format for analysis
- Handled outliers in pricing
- Standardized all columns for consistent analysis

---

## 📊 Key Analyses Performed
### ✔ Rating Analysis
- Counted how many properties have a rating **above 4.0**
- Identified rating distribution across listings

### ✔ Pricing Insights
- Found high-value and ultra-high-value properties (≥ $10,000)
- Visualized price distribution and outliers

### ✔ Neighborhood & Property Type Analysis
- Compared listings across different neighborhoods
- Analyzed counts and price averages by room type
- Created charts to visualize market trends

---


📈 Visualizations Included
All charts are saved in the plots/ folder, including:
Rating distribution
Price distribution
Heatmap of correlations
Top neighborhoods by listing count
Room type comparison

Made by Devang 

--------------------------END--------------------------------------
