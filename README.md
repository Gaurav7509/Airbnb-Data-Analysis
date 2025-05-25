# Airbnb Data Analysis – Review 1: Data Preprocessing & EDA

## 📌 Project Overview

This project analyzes Airbnb-style real estate sales and amenities data across zip codes in California. It focuses on data cleaning, preprocessing, exploratory data analysis (EDA), and generating meaningful insights through visualizations.

## 📁 Folder Structure
airbnb-data-analysis-review1/
 - ├── data/
 - │   ├── market_analysis_2019.csv
 - │   ├── sales_properties_total_zipcode_92252.csv
 - │   ├── sales_properties_total_zipcode_92284.csv
 - │   ├── sales_properties_total_zipcode_92314.csv
 - │   ├── sales_properties_total_zipcode_92315.csv
 - │   ├── sales_properties_with_pool_zipcode_92252.csv
 - │   ├── sales_properties_with_pool_zipcode_92284.csv
 - │   └── amenities.csv
 - ├── notebooks/
 - │   └── airbnb_eda_review1.ipynb
 - ├── plots/
 - │   ├── price_distribution.png
 - │   └── listings_map.html
 - ├── presentation/
 - │   └── airbnb_review1_presentation.pptx (you’ll upload after generation)
 - ├── README.md
 - ├── requirements.txt



## 🧪 Datasets Used

- Sales properties by ZIP (with/without pool)
- Amenities dataset
- Market analysis summary (2019)

## 🧼 Preprocessing & EDA Tasks

- Handled missing values and dropped duplicates
- Transformed columns where necessary
- Filtered and engineered new features
- Checked for and removed outliers
- Ensured data consistency across files

## 📊 Visualizations

Saved to the `plots/` folder:
- Price distributions
- Map of listings by price
- Room types and availability
- Amenity comparisons (if applicable)

## ▶️ How to Run

```bash
pip install -r requirements.txt
cd notebooks
jupyter notebook airbnb_eda_review1.ipynb

---


## 📦 `requirements.txt`


```txt
pandas
matplotlib
seaborn
plotly
jupyter
---
