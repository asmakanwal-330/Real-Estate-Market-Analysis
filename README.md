# Real Estate Market EDA Project-


Project  Title
 🏘️ Real Estate Market Insights: An Exploratory Analysis of Zameen.com Listings in Pakistan

Welcome to this project repository where we dive deep into the Pakistani real estate market using data from Zameen.com. The goal of this exploratory data analysis (EDA) is to extract insights that can help investors and buyers make informed decisions  based on trends, pricing, and listing quality.

🎯 Project Objective

To explore and analyze property listings on Zameen.com and uncover:

* Key pricing trends
* Neighborhood comparisons
* Listing quality indicators
* Data-driven recommendations for real estate investors


 🗃️ Dataset Description

The dataset contains the following features scraped from Zameen.com:

* 📍 Location (City, Area) 
* 💰 Price
* 🏠 Property Type 
* 📐 Area (e.g., Marla, Kanal, Sqft)
* 🛏️ Number of Rooms,Bedrooms  and  other 57 Features
* 📅 Built in year
* 📝 Listing Title & Description


 🔍 EDA Workflow Overview

 1. 🧩 Problem Statement

> What are the factors that drive real estate prices in major Pakistani cities?

 2. 📊 Data Understanding & Preprocessing

* Explored structure with Pandas
* Checked duplicates, cleaned currency symbols
* Converted units (e.g., Marla/Kanal → Sqft)


 3.  Missing Value Treatment
    Addressed missing values with EDA techniques


 4. 🔍 Data Cleaning & Consistency

* Standardized city and area names using FuzzyWuzzy library
* Detected and handled outliers with IQR 
* Unified property types


5. ✨ Feature Engineering

* Derived new variables for enhanced insights (e.g., price per sqft) and Propert category(Residential/Commercial)


 6. 📉 Univariate & Bivariate Analysis

* Distribution plots for price, area
* Heatmaps for correlations
* Box plots for price comparisons across  Area, Price, and bed counts


7. 💡 Insights & Recommendations

* Highlighted top-performing  Property Categories with area(sqr ft.)for investment
* Identified property types with high demand
* Suggested filters for efficient buyer targeting


 8. 🧾 Conclusion & Next Steps

* Summarized  my learnings  
* Recommended Key areas for  future work 





