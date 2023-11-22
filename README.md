# Spotify-Popularity-Prediction-Analysis-and-Modeling

## Overview

Welcome to the Spotify Popularity Prediction project! In this analysis, I explore the intricacies of the Spotify dataset to understand the factors influencing the popularity of tracks. Leveraging Python and powerful libraries such as Pandas, Matplotlib, Seaborn, and XGBoost, I delved into data cleaning, exploratory data analysis (EDA), feature engineering, and model training to predict track popularity.

## Key Steps and Findings

### 1. Data Cleaning and Exploration
- **Handling Missing Data:** Addressed missing values and ensured data integrity.
- **Duplicate Removal:** Removed duplicate entries for a cleaner dataset.
- **Initial Analysis:** Explored numerical and categorical features, revealing insights into the data structure.

### 2. Exploratory Data Analysis (EDA)
- **Numerical Features:** Investigated relationships between numerical features and popularity.
- **Categorical Features:** Explored the impact of categorical variables on track popularity.
- **Outlier Detection:** Identified outliers in various features.
- **Speechiness Analysis:** Analyzed the distribution of speechiness types and their correlation with popularity.

### 3. Feature Engineering
- **Speechiness Transformation:** Converted speechiness into discrete categories (High, Medium, Low).
- **Skewness Transformation:** Applied various transformations to reduce skewness in continuous features.
- **Encoding:** Employed BaseN encoding and one-hot encoding for categorical features.

### 4. Model Training and Evaluation
- **Feature Selection:** Used correlation analysis to select relevant features.
- **Model Selection:** Explored several models including Linear Regression, Lasso, Ridge, XGBoost, XGBoost Random Forest, Decision Tree, and Bayesian Ridge.
- **Performance Metrics:** Assessed models using Mean Squared Error (MSE), Absolute Mean Squared Error (ABMSE), and R2 Score.

## Model Performance

Among the models considered, XGBoost and Decision Tree emerged as top performers for predicting track popularity. The XGBoost Regressor exhibited the highest R2 Score and the lowest Mean Squared Error, making it the preferred model for future predictions.

4. **Contribute:**
   Feel free to contribute by opening issues, providing feedback, or submitting pull requests. Your insights and improvements are highly valued!

## Contact

For questions, suggestions, or collaborations, feel free to reach out:

- Email: donmoendevdas@gmail.com
