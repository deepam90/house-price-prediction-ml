House Price Prediction: Advanced Feature Engineering & Regression

📌 Project Overview

Predicting residential house prices is a classic regression problem, but the real challenge lies in the data quality. This project focuses on building a robust machine learning pipeline that handles high-cardinality categorical variables and complex missing data patterns to improve model accuracy.

🛠 Tech Stack

Language: Python 3.x

Libraries: * Pandas & NumPy: For data manipulation and matrix operations.

Scikit-Learn: For pipeline building, scaling, and regression models.

Matplotlib & Seaborn: For correlation heatmaps and distribution analysis.

Environment: Jupyter Notebook / Anaconda

🚀 Technical Highlights & Feature Engineering

This project stands out because of the following advanced preprocessing steps:

Handling Missing Values: * Imputed "Missing" for categorical features where the absence of a feature (like 'Pool' or 'Alley') was significant.

Used statistical measures (Median/Mean) for numerical missing values.

Rare Label Management: * Identified categorical labels that appeared in less than 1% of the dataset and grouped them into a "Rare" category to prevent model overfitting.

Temporal Feature Engineering: * Created new features by calculating the "Age of the House" at the time of sale (Year Sold - Year Built).

Log Transformation: * Applied log transformation to skewed numerical variables to achieve a normal distribution, enhancing the performance of linear algorithms.

Categorical Encoding: * Performed mapping of ordinal variables and One-Hot Encoding for nominal variables.

📊 Key Results

EDA Insights: Identified that Overall Quality, GrLivArea (Above ground living area), and GarageCars were the strongest predictors of sale price.

Model Performance: Achieved a competitive Error Rate (RMSE/MAE) by focusing heavily on feature selection and scaling.

