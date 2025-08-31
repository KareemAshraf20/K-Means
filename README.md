# Marketing Campaign Customer Segmentation using K-Means

## 📌 Project Overview
This project analyzes a marketing campaign dataset to perform customer segmentation using K-Means clustering. The goal is to identify distinct customer groups based on their behavior and demographics, which can help businesses tailor their marketing strategies more effectively.

## 📊 Dataset
The dataset used is `marketing_campaign.csv`, which contains information about 2240 customers and includes 29 features such as:
- Customer demographics (Year_Birth, Education, Marital_Status, Income)
- Customer behavior (Recency, MntWines, MntFruits, NumWebPurchases, etc.)
- Campaign responses (AcceptedCmp1-5, Response)
- Other relevant attributes

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
  
## 🚀 Implementation Steps

### 1. Importing Libraries

### 2. Data Loading and Initial Exploration
- Loaded the dataset using pandas.
- Checked the shape, data types, and basic information of the dataset.

### 3. Data Preprocessing
- Converted `Dt_Customer` to datetime format.
- Handled missing values (e.g., Income had 24 missing values).
- Dropped irrelevant columns (ID, Z_CostContact, Z_Revenue).
- Performed exploratory data analysis (EDA) to understand data distribution and correlations.

### 4. Clustering with K-Means
- Used K-Means clustering to segment customers.
- Determined the optimal number of clusters using the Elbow Method.
- Standardized features using StandardScaler to ensure equal weighting.

### 5. Visualization
- Visualized clusters using scatter plots and other relevant plots.
- Analyzed cluster characteristics to derive business insights.

## 📈 Results
- Identified [X] distinct customer segments.
- Each segment exhibited unique behaviors and demographics.
- Provided actionable insights for targeted marketing campaigns.
