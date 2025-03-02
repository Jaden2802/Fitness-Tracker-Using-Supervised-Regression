
#Fitness Tracker Data Analysis & Price Prediction

📌 Project Overview

This project focuses on analyzing fitness tracker data to understand price trends and predict selling prices using machine learning models. Various regression techniques are applied to evaluate the best predictive model.

📂 Dataset

Dataset Name: Fitness_trackers_updated.csv

Columns:

Brand: Manufacturer of the fitness tracker

Model: Product model name

Category: Smartwatch or Fitness Band

Features: Various specifications like Display Type, Battery Life, Sensors, etc.

Original Price: The listed price of the device

Selling Price: The discounted or actual selling price

Other attributes related to materials, display, battery, and features

📊 Exploratory Data Analysis (EDA)

Handling missing values

Data cleaning (removing duplicates, encoding categorical values)

Feature selection & engineering

Visualizing correlations with heatmaps & scatter plots

🏗️ Machine Learning Models Used

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Support Vector Regressor (SVR)

🎯 Performance Evaluation

Accuracy (R² Score) 97.48 %

Cross-Validation Score (5-Fold R² 85.09 %)

🛠️ Installation & Setup

Install dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn

Run the analysis script:

python analysis.py

📌 Results & Insights

Identified key features affecting selling prices

Compared multiple regression models to find the best predictor

Used cross-validation to validate the robustness of models

📜 Future Scope

Improve model accuracy with feature engineering

Integrate a real-time price prediction API

Deploy the model using Flask or FastAPI

🤝 Contributing

Feel free to fork, create pull requests, or open issues for improvements.


🚀 Let's predict fitness tracker prices with data science!
