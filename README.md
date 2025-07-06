# Laptop-Price-Predictor
The Laptop Price Predictor is a machine learning project that estimates the price of a laptop based on its specifications. Built using the Random Forest Regression algorithm, this project demonstrates how structured product data can be used to predict prices with high accuracy, making it useful for buyers, sellers, or e-commerce platforms.

Project Overview:
The model is trained on a dataset of laptops with features like:

Brand

Processor (CPU)

RAM size and type

Storage type and capacity (SSD/HDD)

GPU

Display size and resolution

Operating System

Weight, Touchscreen, and more

These features are preprocessed and transformed into numerical formats using encoding techniques to make them suitable for machine learning. The cleaned data is then used to train a Random Forest Regressor, known for its robustness and ability to handle non-linear relationships between features.

Key Features:
Predict laptop prices based on user-specified hardware configurations

Data preprocessing including handling of categorical features, feature engineering, and outlier removal

Trained using Random Forest, with hyperparameter tuning for better performance

Evaluation using R² Score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE)

Optional Streamlit web app for interactive predictions
