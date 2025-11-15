# House_Price_Prediction_Model
## 🏠 California Housing Price Prediction using Machine Learning

This project focuses on predicting median house prices in California using real-world data from Scikit-Learn’s California Housing Dataset.
Multiple regression techniques were applied to analyze factors affecting real estate value and improve model performance.

📌 Problem Statement

California housing prices vary widely based on:

Local income

Geographic location

House features

Population density

### This project aims to:  
✔ Identify key factors affecting house prices  
✔ Build a predictive model using different ML algorithms  
✔ Compare performance using regression metrics & visuals  

## 📊 Dataset Information

The dataset contains 20,640 housing records with 9 features:

### Column	Description

1. longitude, latitude	Geographical location  
2. housing_median_age	Age of property area
3. total_rooms	Total number of rooms in the area
4. total_bedrooms	Total number of bedrooms
5. population	Number of people living in the area
6. households	Total households
7. median_income	Average income of residents
8. ocean_proximity	Distance from the coastline
9. Price (target)	Median house value in USD  

Source: Included within Scikit-Learn datasets  

## 🧠 Tech Stack & Tools Used  

### Tool / Library	Purpose  

Python	Programming  

Pandas, NumPy	Data cleaning & preprocessing  

Seaborn, Matplotlib	Data visualization  

Scikit-Learn	Regression modeling  

XGBoost	Performance improvement  

Jupyter Notebook	Development environment  

## 🔍 Exploratory Data Analysis (EDA)  

Key relationship findings:  

Median income has the strongest positive correlation with price (0.69)  
Houses near ocean are significantly more valuable    
Inland properties show negative impact on pricing  
Bedrooms, population show weak influence  

Visuals included:  

1. Correlation Heatmap
2. Pairwise Scatter Plots
3. Actual vs Predicted Score Graphs  

## 🤖 Machine Learning Models Used  

1. Model Used	Purpose	Performance (R²)
2. Linear Regression	Baseline model	~0.62
3. Polynomial Regression	Capture non-linear patterns	Improved
4. XGBoost Regressor	Best learning performance	>0.85   

## 📈 Model Evaluation Metrics  

1. Metric	Result	Meaning  
2. MAE	50,670	Avg prediction error  
3. RMSE	70,060	Penalty for large errors  
4. R²	0.6254	Baseline model explained variance  

XGBoost model achieved the highest accuracy and best visual alignment with real prices.  

## 📌 Key Takeaways

House prices depend strongly on income levels 

Coastal homes are significantly more expensive  

Real estate pricing is highly non-linear → advanced models recommended  

Feature scaling greatly improves regression performance  

## 🙌 Author
Rehan  
Machine Learning Practitioner | Data Science Enthusiast  
