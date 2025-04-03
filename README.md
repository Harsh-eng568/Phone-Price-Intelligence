# Phone-Price-Intelligence
# **Project Title: Mobile Price Prediction and Classification**  

## **Project Goal**  
The project aims to analyze a smartphone dataset to understand the **factors influencing mobile prices** and build models for **price prediction and classification**.

---

## **Data Used**  
The dataset **'smartphone_cleaned_v5.csv'** contains information about various smartphones, including:  
- **Brand**  
- **Price**  
- **Technical specifications**  
- **Features** (e.g., processor, RAM, battery, etc.)

---

## **Steps & Analysis Performed**  

### **1. Exploratory Data Analysis (EDA)**  
- Explored the dataset structure, statistics, and distributions.  
- Visualized price distribution, brand popularity, and feature relationships using **Pandas, Matplotlib, and Seaborn**.  
- Identified and handled missing data.

### **2. Price Prediction**  
- Applied **feature engineering**:  
  - One-hot encoding & label encoding for categorical variables like **brand** and **OS**.  
- Used **feature selection** to identify the most correlated features with price.  
- Applied **regression models** (e.g., `RandomForestRegressor`) to predict smartphone prices.  
- Evaluated performance using:  
  - **Mean Squared Error (MSE)**  
  - **R-squared (R²) score**  

### **3. Price Classification**  
- Defined a **binary classification problem** by categorizing smartphones into:  
  - **High Price**  
  - **Low Price**  
  *(Based on the median price threshold)*  
- Used **ANOVA F-test** for feature selection to find the **top 10 most relevant features**.  
- Trained a **Logistic Regression model** for classification.  
- Optimized using **GridSearchCV** to tune hyperparameters (`C` and `max_iter`).  
- Evaluated classification performance using:  
  - **Accuracy**  
  - **Precision**  
  - **Recall**  

---

## **Outcome & Key Findings**  
✅ **Insights into factors influencing mobile prices**.  
✅ **Developed a regression model** to predict smartphone prices.  
✅ **Built a classification model** for categorizing mobile prices.  

### **Key Findings:**  
- **Price is influenced by factors such as brand, processor, RAM, and specifications.**  
- **ANOVA F-test identified the top 10 features for classification.**  
- **Logistic Regression achieved a certain accuracy in classifying mobile prices.**  

---

## **Further Analysis & Improvements**  
🚀 **Test alternative regression and classification models** for better performance.  
🚀 **Incorporate additional features or datasets** for more comprehensive analysis.  
🚀 **Deploy the model for real-world smartphone price prediction.**  
