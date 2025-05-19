<h1> Apartment Price Prediction in Daegu </h1>

## 1. Project Overview
This project analyzes business data to extract insights, improve decision-making, and identify key trends. The primary focus is to **predict apartment prices in Daegu, South Korea**, based on various features such as type, size, and surrounding infrastructure. The project aims to support real estate stakeholders (developers, investors, homebuyers) in making data-driven decisions.

Key Objectives:
- Objective 1: Analyze housing and demographic data from Daegu.
- Objective 2: Build machine learning models to predict apartment prices.
- Objective 3: Evaluate and select the best-performing model based on regression metrics.

## 2. Data Sources
- `Daegu_Real_Estate.csv` – Contains apartment sales data with various features like type, size, year built, etc.

## 3. Technologies Used
- Programming Language: Python (Pandas, NumPy)
- Modeling: Linear Regression, Decision Tree, Random Forest, XGBoost, K-Nearest Neighbors
- Preprocessing: OneHotEncoding, OrdinalEncoding, Iterative Imputer, Scalers (MinMax, Standard, Robust)
- Visualization: Matplotlib, Seaborn, SHAP
- Model Evaluation: MAE, MSE, RMSE, MAPE, R² Score
- Optimization: GridSearchCV, RandomizedSearchCV
- Others: Jupyter Notebook, Scikit-learn, Yellowbrick, Joblib

## 4. Project Structure
├── README.md

├── data

│ └── raw <- Daegu_Real_Estate.csv

│

├── models <- Saved models using joblib

│

├── notebooks <- Capstone Modul 3.ipynb

│

├── reports <- Visualizations, SHAP plots, learning curves

│ └── figures

│

└── src <- Preprocessing pipelines, model training scripts


## 5. Summary of Finding
### 5.1 Business Insight
- Despite declining population, housing demand persists due to household expansion.
- Key predictors of apartment prices include location, year built, and size.
- Machine learning models, XGBoost outperform baseline models in prediction accuracy.

### 5.2 Actionable Recommendation
- Stakeholders should monitor infrastructure development projects when evaluating property investment.
- Model predictions can be integrated into pricing tools for property agents and developers.
- Further feature engineering (e.g., proximity to metro, schools) may improve accuracy.

## 6. Contact
- Name: Satrio Bagus Prabowo
- Email: satriobagusp.8@gmail.com
- Linkedin: https://www.linkedin.com/in/satrio-bagus-prabowo/
