# Real-Estate-Market-Analysis-using-Selenium-and-EDA
Hyderabad Real Estate Market Analysis using Selenium and Python. Collected property data from MagicBricks, performed data cleaning, feature engineering, EDA (univariate, bivariate, multivariate), and hypothesis testing (ANOVA) to uncover pricing trends, location insights, and key real estate market patterns.
# 🏠 Hyderabad Real Estate Market Analysis

## 📌 Overview
This project analyzes Hyderabad's residential real estate market using data collected from MagicBricks through Selenium web scraping. The goal is to uncover pricing trends, location-based insights, and key factors influencing property values through data analysis and statistical testing.

## 🎯 Business Problem
The real estate market contains thousands of listings with varying prices, locations, and property features. Buyers, investors, and sellers need data-driven insights to make informed decisions. This project helps identify market trends and pricing patterns in Hyderabad's housing market.

## 🛠️ Technologies Used
- Python
- Selenium
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## 📂 Data Collection
Data was scraped from MagicBricks using Selenium. Key features collected include:
- Price
- Location
- BHK
- Carpet Area
- Super Area
- Bathrooms
- Balconies
- Property Type
- Furnishing Status
- Price per Sqft

## 🔧 Data Preprocessing
- Handled missing values
- Removed duplicates
- Cleaned and transformed data
- Converted data types
- Standardized formats

## ⚙️ Feature Engineering
- Area Efficiency = Carpet Area / Super Area

## 📊 Exploratory Data Analysis (EDA)
### Univariate Analysis
- Price Distribution
- BHK Distribution
- Area Distribution
- Location Frequency

### Bivariate Analysis
- BHK vs Price
- Area vs Price
- Location vs Price
- Price per Sqft Analysis

### Multivariate Analysis
- Correlation Analysis
- Pairplots
- Heatmaps

## 📈 Hypothesis Testing
### ANOVA Test: BHK vs Price
**H₀:** Property prices do not differ significantly across BHK categories.  
**H₁:** Property prices differ significantly across BHK categories.

## 🔍 Key Insights
- Property prices vary significantly across Hyderabad locations.
- BHK has a significant impact on property prices.
- Premium localities have higher price per sqft.
- Larger properties generally command higher prices.
- Area efficiency provides additional property valuation insights.

## 📁 Project Workflow
Web Scraping → Data Collection → Data Cleaning → Feature Engineering → EDA → Hypothesis Testing → Insights & Recommendations

## 🚀 Future Scope
- Property Price Prediction Model
- Power BI Dashboard
- Automated Data Pipeline
- Advanced Statistical Analysis

## 👨‍💻 Author
Harish Alakuntla

⭐ If you found this project useful, give it a star!
