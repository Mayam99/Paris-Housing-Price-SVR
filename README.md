# Paris Housing Price Prediction with SVM Regression

This project focuses on predicting housing prices in Paris by implementing Support Vector Machine (SVM) Regression and optimizing it with Hyper-Parameter Tuning. Leveraging SVM, a robust algorithm suited for handling complex datasets, this project aims to model the relationships between housing features and price, enabling precise and data-driven predictions for the Paris housing market.

Project Overview

The dataset, sourced from Kaggle, includes essential features like house size, location, and amenities, each of which impacts housing prices. The project workflow includes:

* Data Preprocessing: Cleaning and preparing the data, including feature scaling and encoding, to ensure compatibility with the SVM model.
* Model Training: Building an initial SVM regression model and tuning its hyper-parameters (C, epsilon, and kernel type) using GridSearchCV to achieve optimal predictive accuracy.
* Evaluation: Using key regression metrics—MAE, MSE, RMSE, and R²—to evaluate model performance and assess prediction accuracy.

Key Features

* Hyper-Parameter Tuning: Fine-tunes the model for better generalization and precision.
* Scalability: Model can be adapted and scaled to similar housing datasets, making it versatile for various applications in real estate.
* Performance Visualization: Actual vs. predicted price visualizations to better interpret model results.

Technologies Used

* Python: Programming language for implementation.
* Scikit-Learn: For machine learning model building and evaluation.
* Pandas & NumPy: For data manipulation.
* Matplotlib & Seaborn: For visualizations.
