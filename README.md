# NBA_Player_Price_Prediction
Introduction:
The NBA Player Price Prediction project aims to predict the market value of NBA players based on various features using machine learning techniques. The project involves data preprocessing, exploratory data analysis, feature engineering, model selection, and creating a user-friendly web application for interactive predictions using Streamlit.

Dataset:
The dataset used in this project was obtained from Kaggle and contains information about NBA players, including their statistics, performance metrics, physical attributes, and market values.

Data Preprocessing:
Data preprocessing is a crucial step in any machine learning project to clean and transform raw data into a suitable format for analysis and modeling. This step involves handling missing values, removing duplicates, and converting categorical variables into numerical representations.

Exploratory Data Analysis (EDA):
EDA involves visualizing and summarizing the dataset to gain insights into the relationships between variables and identify potential patterns. Visualizations such as scatter plots, histograms, and correlation matrices can help in understanding the distribution of features and their correlations with the target variable (player price in this case).

Feature Engineering:
Feature engineering is the process of creating new features or transforming existing features to improve the performance of machine learning models. In this project, you might have created new features such as player efficiency ratings, team performance metrics, and player experience level. These engineered features can provide additional information for the prediction model to leverage.

Model Selection:
For predicting NBA player prices, you chose the XGBoost regressor. XGBoost is an ensemble learning algorithm that combines the predictions of multiple decision trees to provide accurate predictions. It is particularly effective for regression tasks and handles non-linear relationships well.

Training the XGBoost Model:
You split the dataset into training and testing sets to evaluate the model's performance. The training set was used to train the XGBoost regressor using the features generated through preprocessing and feature engineering. Hyperparameter tuning may have been conducted to optimize the model's performance.

Data Visualization:
Throughout the project, various visualizations were created using libraries like Matplotlib and Seaborn. These visualizations helped in presenting insights to stakeholders and also aided in understanding the distribution of features, the importance of different features in the model, and the model's predictions.

Creating the Web App with Streamlit:
To make your project accessible and user-friendly, you developed a web application using Streamlit. Streamlit is a Python library that allows you to create interactive web applications for data science projects with minimal code. The web app likely allows users to input the features of an NBA player and get a predicted price based on the trained XGBoost model.

# Video For Explanation -
[streamlit-app-2023-09-20-22-09-45.webm](https://github.com/ParvSoni/NBA_Player_Price_Prediction_Streamlit_App/assets/123165567/d028658e-a648-4ffb-a2cf-972151cd1f2d)

