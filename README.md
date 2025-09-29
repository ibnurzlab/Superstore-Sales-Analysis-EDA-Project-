# 🛒 Superstore Sales Analysis (EDA Project)

## 📌 Project Description
This project is an **Exploratory Data Analysis (EDA)** on the `superstore_data.csv` dataset, which contains sales, customer, and product-related information.  
The main objective is to understand the dataset, clean and preprocess it, analyze distributions, and extract insights about sales performance, customer characteristics, and potential business opportunities.

## 📂 Dataset
- **File Name:** `superstore_data.csv`  
- **Features Overview:**
  - `Customer` information (e.g., name, segment, region)  
  - `Product` details (e.g., category, sub-category, sales, profit)  
  - `Income` and financial attributes  
  - `Order` information (e.g., order ID, shipping details, date)  

## 🛠️ Tools & Libraries
This project was developed in **Python** with the following libraries:
- `pandas` & `numpy` → data loading and manipulation  
- `matplotlib` & `seaborn` → data visualization  
- `warnings` → suppressing irrelevant warnings  

## 🔍 Analysis Workflow
1. **Data Understanding**
   - Load and inspect dataset structure (`shape`, `head`, `info`, `describe`).  
   - Explore categorical and numerical features.  

2. **Data Cleaning**
   - Identify and handle missing values (e.g., in `Income`).  
   - Visualize outliers using histogram and boxplots.  
   - Apply preprocessing and corrections as needed.  

3. **Exploratory Data Analysis**
   - Analyze feature distributions (e.g., `Income`, sales, profit).  
   - Visualize categorical attributes (e.g., customer segments, regions, product categories).  
   - Explore relationships between numerical features.  

4. **Insights**
   - Identify factors influencing income and sales.  
   - Detect data anomalies and outliers.  
   - Highlight business opportunities based on customer and product patterns.  

## 📊 Key Findings
- Missing values found in the `Income` column, requiring cleaning.  
- Income distribution shows presence of outliers, confirmed by histogram and boxplot.  
- Sales and profit trends vary across product categories and customer segments.  
- Visualization highlights differences in customer purchasing behavior.  
