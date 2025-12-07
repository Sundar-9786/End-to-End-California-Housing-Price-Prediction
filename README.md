# End-to-End-California-Housing-Price-Prediction



📌 Project Overview
This project is an end-to-end Machine Learning initiative to predict median housing prices in various districts of California. Using data from the 1990 California census, the project involves comprehensive data analysis, advanced feature engineering (including geospatial clustering), and hyperparameter tuning of ensemble models.

🚀 Key Features
Automated Data Fetching: Script to download and extract tarball data directly from the source.

Exploratory Data Analysis (EDA): Visualization of geographical data and feature distributions.

Feature Engineering:

Creation of interaction features (e.g., bedrooms_per_room).

Geospatial Clustering: Used K-Means to group districts by location and measure similarity to cluster centers.

Gaussian transformations (Log) for skewed features.

Transformation Pipelines: Modular preprocessing using Scikit-Learn's Pipeline and ColumnTransformer.

Model Tuning: Advanced hyperparameter tuning using RandomizedSearchCV.

🛠️ Technologies Used
Python 3.x

Pandas & NumPy for data manipulation.

Matplotlib for data visualization.

Scikit-Learn for modeling, preprocessing, and clustering.

📊 Model Performance
The project compares several models including Linear Regression and Decision Trees, ultimately selecting a Random Forest Regressor. The final model was fine-tuned to achieve a competitive RMSE (Root Mean Squared Error) on the validation set.
