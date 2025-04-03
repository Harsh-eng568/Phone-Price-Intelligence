# Phone-Price-Intelligence
# **Smartphone Price Analysis & Classification**

## **Project Goal**  
The project aims to analyze a smartphone dataset to understand the factors influencing mobile prices and build models for price prediction and classification.  

## **Dataset**  
The dataset used is **'smartphone_cleaned_v5.csv'**, which contains smartphone specifications such as brand, price, processor, RAM, battery capacity, and other features.  

---

## **1️⃣ Data Cleaning**  
✔️ Handled missing values by removing or imputing data.  
✔️ Encoded categorical variables (**brand, processor, OS**) using **Label Encoding & One-Hot Encoding**.  
✔️ Removed duplicate and irrelevant columns.  
✔️ Standardized numerical features for better model performance.  

---

## **2️⃣ Exploratory Data Analysis (EDA)**  
📊 Explored dataset structure, statistics, and distributions.  
📊 Visualized **price distribution, brand popularity, and feature relationships** using **Pandas, Matplotlib, and Seaborn**.  
📊 Identified and handled **outliers**.  

---

## **3️⃣ Price Prediction (Regression)**  
✅ Selected top features correlated with price using **Feature Selection**.  
✅ Applied **Random Forest Regressor** to predict smartphone prices.  
✅ Evaluated model performance using **Mean Squared Error (MSE) and R-squared**.  

---

## **4️⃣ Price Classification (Logistic Regression)**  
🔹 Converted price into a **binary category ('High' or 'Low')** based on the median price.  
🔹 Used **ANOVA F-test** to select the **top 10 features** for classification.  
🔹 Applied **Logistic Regression** with hyperparameter tuning (**GridSearchCV**).  
🔹 Evaluated the model using **accuracy, precision, and recall**.  

---

## **🔍 Key Findings**  
✔️ **Brand, processor, RAM, and battery capacity significantly influence smartphone prices.**  
✔️ **ANOVA F-test** revealed the top 10 most important features for classification.  
✔️ **Logistic Regression** achieved a strong accuracy in categorizing smartphone prices. 

---

## **Further Analysis & Improvements**  
🚀 **Test alternative regression and classification models** for better performance.  
🚀 **Incorporate additional features or datasets** for more comprehensive analysis.  
🚀 **Deploy the model for real-world smartphone price prediction.**  
