# 💳 Credit Card Usage Segmentation

## 📌 Project Overview
This project aims to segment credit card users based on their spending behavior and payment patterns using unsupervised learning techniques. The goal is to help financial institutions understand customer groups better, personalize services, and improve marketing strategies.

## 🧠 Problem Statement
Credit card companies handle massive volumes of customer transaction data, but without proper segmentation, it’s difficult to tailor offerings or manage risk effectively. Clustering helps group similar customers based on usage patterns for strategic decision-making.

## 🔧 Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- KMeans, PCA
- Jupyter Notebook

## 📊 Methodology
1. **Data Cleaning & Preprocessing**
   - Handled missing values (e.g., `MINIMUM_PAYMENTS`)
   - Scaled numeric features for clustering

2. **Exploratory Data Analysis (EDA)**
   - Analyzed variables like `BALANCE`, `PURCHASES`, `CASH_ADVANCE`, `TENURE`, etc.
   - Identified relationships and trends in spending behavior

3. **Clustering**
   - Used K-Means clustering to segment customers
   - Applied PCA to reduce dimensionality and visualize clusters
   - Determined optimal number of clusters using the Elbow Method

4. **Interpretation**
   - Described each cluster's behavior (e.g., high spenders, balanced users, cash-advance-heavy users)

## ✅ Results
- Segmented customers into meaningful groups
- Provided actionable insights for targeted marketing and service personalization
- Visualized cluster patterns using PCA and Seaborn plots

> 👩‍💻 Created by: Rishita shah  
> 📅 Project Date: 2024
