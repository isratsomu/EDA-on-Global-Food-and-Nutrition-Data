# 🍎 Exploratory Data Analysis of Global Food and Nutrition Data

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a global food supply and nutrition dataset. The objective is to understand how the food supply of different countries (meat, cereals, vegetables, sugar, etc.) is related to health outcomes such as obesity and undernourishment. The project demonstrates data cleaning, indexing, grouping, statistical analysis, and visualization techniques used by data scientists.

## 📂 Dataset

**COVID-19 Healthy Diet Dataset** (Kaggle, by mariaren)
https://www.kaggle.com/datasets/mariaren/covid19-healthy-diet-dataset

File used: `Food_Supply_Quantity_kg_Data.csv` (one row per country, 154 countries after cleaning).

## 🔎 Exploratory Data Analysis Workflow

**A. Understand your data**
1. Import the dataset as a pandas DataFrame
2. How does the data look like?
3. How big is the data?
4. What is the data type of each column?
5. How does the data look like mathematically?
6. Are there any missing values?
7. Are there any duplicated values?
8. List the top 10 countries with the highest obesity
9. List the top 10 countries with the lowest obesity
10. Find rows with null values and delete them

**B. Indexing and grouping**
1. Create a Region column and a separate DataFrame for each region
2. Compute the mean obesity for each region and rank the regions
3. Count the countries in each region with obesity above 20

**C. Obesity analysis**: highest, lowest and average obesity

**D. Region-based analysis**: average, maximum and number of countries per region

**E. Feature-based analysis**: which country has the highest and lowest supply of each food group

**F. Correlation and relationship**: correlation of obesity with all variables, variables above 0.7, negative correlations, and the most correlated pair of variables

**G. Bar plots**: Top 10 countries, stacked bar of food composition for the Top 10, and stacked bar for all African countries

**H. Histogram**: distribution of obesity and undernourishment

**I. Pairwise scatter plots**: obesity versus each food group

**J. Heatmap**: correlation heatmaps

## 📝 Key Findings

1. Samoa has the highest obesity rate (45.5), and Vietnam has the lowest (2.1).
2. The average obesity rate across 154 countries is 18.45.
3. The region with the highest average obesity is Oceania (30.32).
4. The region with the lowest average obesity is Africa (10.52).
5. Meat has the strongest positive correlation with obesity (0.56).
6. Undernourished has the strongest negative correlation with obesity (-0.57).

Note: correlation shows a relationship, not proof of cause.

## 🛠️ Tools Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab

## ▶️ How to Run

1. Download the dataset from the Kaggle link above.
2. Open the notebook in Google Colab (File → Upload notebook).
3. Run all cells and upload `Food_Supply_Quantity_kg_Data.csv` when asked.
