# Tumor_Detection-project
📌 Project Overview
This project aims to predict tumor malignancy (benign vs. malignant) using a Random Forest Classifier on the Wisconsin Breast Cancer Dataset. The workflow includes data cleaning, exploratory analysis, feature selection, and model evaluation.

Key Skills Demonstrated:
✔ Data Preprocessing
✔ Feature Importance Analysis
✔ Machine Learning (Random Forest)
✔ Visualization with Matplotlib/Seaborn

🔍 Methodology
1. Data Cleaning
Removed irrelevant columns (id).
Checked for missing values (none found).

2. Exploratory Data Analysis (EDA)
Class Distribution: 62% Benign, 38% Malignant.
Correlation Analysis: Identified top features (e.g., concave points_worst) using a heatmap.
Visualizations:
Count plot for diagnosis distribution
Feature correlation heatmap

3. Preprocessing
Standard Scaling: Applied StandardScaler to normalize features.
Train-Test Split: 80% training, 30% testing.

4. Modeling (Random Forest)
Trained a RandomForestClassifier with 150 trees and max_depth of 7.
Evaluated using accuracy, confusion matrix, and classification report.

5. Feature Importance
Identified top 10 influential features (e.g., concave points_worst, perimeter_worst).

## Key Findings
Data Quality: No missing values; only id column dropped.

Class Balance: 
62% Benign (B), 38% Malignant (M).

Top Features:
concave points_worst (Highest importance)
perimeter_worst
radius_worst

Model Performance: 
97% accuracy with Random Forest.
