# 🏡 Airbnb Data Visualization & Analysis Project

![Airbnb Banner](https://github.com/iambitttu/Airbnb-Analysis/assets/117813323/07fcc385-d461-46ce-b938-ca8251b02641)

---
## 📖 Project Overview

This project conducts a comprehensive **Airbnb data analysis and visualization** leveraging datasets from various California ZIP codes. The primary objective is to extract **actionable insights** about pricing, amenities, seasonal patterns, and location-based trends using advanced EDA and interactive visual tools.


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

## 📚 Storytelling with Data

Every Airbnb listing tells a story — of traveler expectations, host strategies, and market dynamics. Through this project, we uncovered compelling narratives embedded in the data that help both **hosts** and **travelers** make informed decisions.

- 🌴 **The Pool Premium**: Imagine two nearly identical homes in California — same size, same location — but one has a pool. Our analysis shows that this simple amenity can increase listing prices by up to **20%**. This trend is particularly strong in warmer ZIP codes like *92284*, where travelers seek leisure-ready properties.

- 🗺️ **The Tale of Two ZIP Codes**: Listings in ZIP **92284** consistently stood out — commanding **higher prices**, boasting **better amenities**, and showing **stronger seasonal demand**. In contrast, other ZIPs showed less consistency, indicating more volatile or niche markets.

- 📆 **Seasons Matter**: The majority of bookings and sales occur in **Q2**, reflecting the travel season peak in California. Hosts listing in early spring can capitalize on this surge, while travelers booking off-season might snag better deals.

- 💰 **Luxury vs. Basic**: Listings offering luxury amenities (e.g., hot tubs, modern kitchens, fast WiFi) had significantly **higher price-per-night rates**. These amenities weren’t just extras — they were **value drivers**, influencing traveler preferences and listing visibility.

- 📉 **Outliers Tell a Story Too**: While most listings followed predictable patterns, a few outliers — either overpriced or under-equipped — revealed misaligned market expectations. Cleaning and analyzing these helped sharpen our insights and remove bias.

By merging **data science techniques** with **human storytelling**, this project doesn't just crunch numbers — it **illuminates patterns, behaviors, and decisions** that shape the Airbnb ecosystem in California.

---

## 🚀 How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Gaurav7509/Airbnb-Data-Analysis.git
   cd Airbnb-Data-Analysis
   4. Run the notebook: Airbnb.ipynb
