🏡 Airbnb Price Prediction & Analytics Project

This project delivers an end-to-end data analytics and machine learning workflow to analyze Airbnb listings and build a predictive model for estimating listing prices. It includes data cleaning, feature engineering, exploratory data analysis (EDA), machine learning modeling, and dashboard-ready outputs for Tableau.

 📊 Project Overview

Airbnb listings contain rich information such as location, room types, amenities, host behavior, and pricing.  
This project aims to:
- Clean and preprocess raw Airbnb data  
- Identify key factors that influence price  
- Visualize correlations and pricing trends  
- Build a Random Forest model to predict listing price  
- Export a cleaned dataset for BI dashboards  
- Provide insights that hosts, analysts, and pricing tools can use  

🧼 Data Cleaning & Feature Engineering

The dataset was cleaned by:
- Handling missing values with median or "Unknown"  
- Removing duplicates  
- Encoding categorical variables  
- Fixing inconsistent formats  
- Removing extreme price outliers (top 1%)  
- Adding time-based features (check-in/check-out hour)

A cleaned dataset was saved for dashboard use.

🔍 Exploratory Data Analysis (EDA)

Key findings:
- Price strongly correlates with bedrooms, bathrooms, accommodates, beds, and neighbourhood
- Entire homes consistently cost more than private/shared rooms  
- Price distribution is right-skewed with luxury outliers  
- Some neighbourhoods form clear price “tiers”  

🔥 Heatmap Visualization  
The correlation heatmap revealed:
- Positive correlation of price with property size features  
- Weak relationship between review scores and price  
- Clear feature importance direction for model building  

🤖 Machine Learning Model
A Random Forest Regressor was chosen for its robustness and accuracy.
Model Performance
- MAE: ~860  
- RMSE: ~11,694  
- R²: ~0.92  

This means the model explains 92% of price variation, performing exceptionally well for real-estate style data.

 📈 Dashboard (Tableau)

A dashboard-ready CSV was created to support:
- Price trends  
- Neighborhood comparisons  
- Room-type insights  
- Host activity patterns  
- Booking behavior  

🛠 Tech Stack

- Python: pandas, numpy, seaborn, scikit-learn, joblib  
- Visualization: matplotlib, seaborn  
- BI Tools:Tableau 
- Version Control: Git & GitHub

🙋‍♀️ Author  
Rimple Patel
Data Analyst | Business Analyst | ML Enthusiast  
⭐ If you like this project, please star the repository!



