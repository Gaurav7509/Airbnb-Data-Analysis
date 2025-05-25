# 🏡 Airbnb Data Visualization & Analysis Project

![Airbnb Banner](https://github.com/iambitttu/Airbnb-Analysis/assets/117813323/07fcc385-d461-46ce-b938-ca8251b02641)

---

## 📖 Project Overview

This project conducts a comprehensive **Airbnb data analysis and visualization** leveraging various datasets, including Airbnb listings, amenities, and sales data across California ZIP codes. The goal is to extract actionable insights about pricing, availability, and regional trends using advanced data cleaning, feature engineering, and visualization techniques.

---

## 🎯 Objectives

- Efficiently clean and handle missing data to ensure reliability.
- Select and engineer meaningful features to improve analysis.
- Ensure data integrity and consistency throughout preprocessing.
- Generate summary statistics and insightful visualizations.
- Identify key patterns, trends, and anomalies in Airbnb listings.
- Handle outliers effectively with suitable data transformations.
- Create initial and interactive visual representations highlighting findings.
- Develop dashboards and apps for dynamic exploration.

---



## 🧪 Datasets Used

- Airbnb listings with pricing and location details
- Amenities data per listing
- Sales properties across various ZIP codes in California
- Market analysis summaries

---
### 📁 Dataset Descriptions

- **market_analysis_2019.csv**: Summary of market trends including median price and volume per ZIP.
- **amenities.csv**: Contains counts of amenities like pool, WiFi, AC per ZIP.
- **sales_properties_with_pool_92252.csv**: Sales data filtered by ZIP and properties with a pool.

---

## 🔧 Data Cleaning & Preprocessing

- Imputation of missing values using appropriate strategies
- Duplicate detection and removal to avoid bias
- Consistent formatting of categorical and date fields
- Outlier detection via Interquartile Range (IQR) and handling
- Log transformations applied to skewed numerical features

---

## ⚙️ Feature Selection & Engineering

- Created new features such as `price_per_sqft`, `has_pool`, `luxury_amenities`
- One-hot encoding for categorical variables (e.g., room type, amenities)
- Aggregated location-based metrics for neighborhood insights
- Seasonal flags added for temporal trend analysis
- Created `price_per_sqft` from price and area to standardize comparisons.
- Created binary flags for amenity presence to assist in correlation analysis.

---

## 📊 Exploratory Data Analysis (EDA)

- Summary statistics generated for all key features
- Correlation matrices and heatmaps reveal relationships
- Visualized distributions with histograms, boxplots, and bar charts
- Geospatial visualizations mapping listings by price and availability
- Time series analysis of availability and pricing trends

---

## 🔍 Key Insights & Patterns

- Pool amenities correlate with 15% higher listing prices on average
- Certain ZIP codes (e.g., 92284) have higher listing densities and demand
- Seasonal fluctuations strongly impact availability and pricing patterns
- Luxury amenities cause significant price variations compared to basic ones
- Listings in ZIP 92284 have the highest average price and pool availability.
- Properties with pools tend to have 15–20% higher average sales price.
- The majority of sales occurred in Q2, indicating a seasonal trend.

---

## 🎨 Visualization Highlights

- Interactive maps with location-based price overlays (via Streamlit)
- Boxplots to identify price distributions by room type and region
- Heatmaps showing seasonal availability trends
- Correlation heatmaps to identify feature relationships
- Dynamic dashboards created in Power BI / Tableau for comprehensive views

---
## 🧼 Outlier Treatment
Used IQR method to remove listings with price 1.5x beyond Q1/Q3 thresholds.

---
## 🧾 Data Dictionary

| Column Name         | Description                                | Type       |
|---------------------|---------------------------------------------|------------|
| `zip_code`          | ZIP code where property is located          | Categorical|
| `price`             | Sale price of the listing                   | Numeric    |
| `has_pool`          | Whether the listing has a pool (1/0)        | Boolean    |
| `listing_date`      | Date when the listing was added             | Date       |

---

## 🚀 How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Gaurav7509/Airbnb-Data-Analysis.git
   cd Airbnb-Data-Analysis

