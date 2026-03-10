# Predictive-Crop-Yield-Analysis-Using-PySpark-and-Tableau

Developed a predictive crop yield analysis system using PySpark and machine learning models. Processed agricultural datasets, performed feature engineering, and built regression and classification models. Used Tableau to visualize insights and analyze factors affecting crop productivity.

* Technologies Used
Python
PySpark
Apache Spark MLlib
Tableau
Machine Learning Models
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Logistic Regression
Decision Tree Classifier
Random Forest Classifier

* The dataset contains agricultural information including:
Crop Type
Crop Year
Season
State
Area Harvested
Production Quantity
Annual Rainfall
Fertilizer Usage
Pesticide Usage
Yield (Production per Area)

* Project Workflow
1. Data Collection
Crop yield dataset obtained from Kaggle.
2. Data Preprocessing
Removed missing values
Encoded categorical variables
Feature engineering using PySpark pipelines
3. Feature Engineering
Created feature vectors using VectorAssembler
Converted categorical variables using StringIndexer and OneHotEncoder
4. Model Development
Implemented regression models for yield prediction
Built classification models to predict yield categories
5. Model Evaluation
Regression metrics: RMSE and R²
Classification metrics: Accuracy and AUC
6. Data Visualization
Created dashboards and plots in Tableau
Analyzed trends between rainfall, production, and crop yield

* Results
The models provided useful insights into the relationship between agricultural factors and crop yield. Decision Tree and Random Forest models showed strong predictive performance compared to baseline models.
The analysis also highlighted the impact of rainfall, fertilizer usage, and pesticide usage on agricultural productivity.

* Impact
This project demonstrates how machine learning and big data analytics can support agriculture by:
Improving crop yield prediction
Supporting better resource management
Helping farmers and policymakers make informed decisions
Enhancing food security planning.

* Future Improvements
Implement advanced models such as Gradient Boosting or Neural Networks
Integrate real-time weather data
Perform spatial and temporal analysis
Deploy the model as a web-based prediction tool
