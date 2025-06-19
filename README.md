Project #11: Predicting Bike Sharing Demand
This project focuses on forecasting the number of bike rentals per hour/day using a machine learning approach. The end goal is to assist city planning and optimize bike distribution to meet urban mobility demands.

Dataset
Dataset: Bike Sharing Demand

The dataset contains historical bike rental information along with features such as date, time, weather, and season.

Problem Type
Type: Regression

Goal: Build predictive models to forecast bike sharing demand.

Models & Techniques Applied
Baseline Models:

Linear Regression

Decision Trees

Random Forest

Advanced Modeling:

XGBoost was applied to extract the best features and enhance prediction performance.

Evaluation Metrics:

RMSE (Root Mean Square Error)

R²-score

Responsibilities & Contributions
Data Loading & Cleaning:

Imported the dataset, handled missing values, and performed data cleaning to prepare it for analysis.

Exploratory Data Analysis (EDA):

Visualized trends and seasonality in the data.

Created correlation heatmaps to understand relationships between variables.

Feature Extraction & Engineering:

Extracted meaningful features such as hour, weekday, season, holiday, and weather conditions.

Focused on handling time-series data with datetime features, ensuring that the temporal patterns were well captured for the forecasting tasks.

Train/Test Split & Evaluation Implementation:

Split the dataset into training and testing subsets while preserving time order.

Implemented evaluation metrics (RMSE, R²-score) to assess model performance accurately.

Visualization:

Visualized the performance of different models to compare results and identify the best model for prediction.

Advanced Model Tuning:

Applied XGBoost not only as an alternative model but also to perform important feature selection and optimization, further driving model improvements.

What I Learned
Throughout this project, I gained hands-on experience in:

Feature Engineering for Time-Series Data: Understanding the importance of datetime features and how to extract useful components like hour, weekday, and season.

Effective Data Splitting: Learning best practices for splitting time-series data to prevent leakage and maintain the temporal order during train/test split.

Model Training & Evaluation: Enhancing my skills in training multiple regression models and correctly implementing standard evaluation metrics such as RMSE and R²-score.

Advanced Feature Selection with XGBoost: Leveraging XGBoost’s capabilities to determine important features and improve prediction quality.

