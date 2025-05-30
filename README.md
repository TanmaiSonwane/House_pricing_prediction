# House_pricing_prediction
Project Overview:
This project involves building a Linear Regression model to predict house prices using the California Housing dataset from sklearn.datasets. The project demonstrates an end-to-end machine learning workflow, including data loading, exploratory data analysis (EDA), preprocessing, model building, evaluation, and prediction.

Dataset:
Source: California Housing Dataset from sklearn.datasets
Description: The dataset contains various features of houses in California such as average rooms, bedrooms, location (latitude & longitude), and the target variable — median house value.

Key Steps and Methodology:
1. Data Loading
Loaded dataset using fetch_california_housing().
Converted the dataset into a Pandas DataFrame for easier manipulation.

2. Exploratory Data Analysis (EDA)
Analyzed feature correlations to identify relationships and potential multicollinearity.
Noted strong correlations between AveRooms & AveBedrms, and Latitude & Longitude.

3. Data Preprocessing
Split the dataset into training and testing sets with a 70:30 ratio.
Applied StandardScaler to normalize the features, ensuring all variables contribute equally to the model.

4. Model Building
Built a Linear Regression model using LinearRegression() from scikit-learn.
Trained the model on the normalized training data.

5. Model Evaluation
Evaluated the model using:
Mean Squared Error (MSE)
Mean Absolute Error (MAE)
R² Score
Adjusted R² Score

The model showed decent predictive performance.

6. Prediction
Made predictions on the test set.
Predicted house price for individual samples using the trained model.
