
Garment Workers Productivity Analysis:


This repository contains the analysis and predictive modeling of garment worker productivity using a dataset from Bangladesh. The goal is to uncover insights that could enhance efficiency and support fair labor practices in the garment industry, which is notorious for low wages and challenging working conditions.

Dataset
The dataset includes 1,197 entries with 14 attributes collected over three months, detailing various aspects such as Standard Minute Value (SMV), work in progress, idle time, overtime, incentives, and actual productivity levels.

Methods
We employed several machine learning models to predict productivity:

Linear Regression: Baseline model.
Ridge and Lasso Regression: Evaluated for their regularization capabilities.
K-Nearest Neighbors (KNN): Assessed for its ability to improve predictions.
Random Forest and Gradient Boosting: Highlighted for their robust performance and ability to capture complex relationships.
Key Findings
Random Forest was the best performing model with the lowest MSE, suggesting its suitability for complex, noisy data.
Important predictors include targeted productivity, SMV, number of workers, and overtime.
Challenges
Balancing simplicity and performance of models.
Model training and hyperparameter tuning complexity.
Recommendations
Implement a standard incentive rate and redefine SMV to optimize work schedules.
Continue leveraging Random Forest for its superior predictive power and robustness to noise.
Tools Used
Python: For all data cleaning, processing, and modeling.
Libraries: Pandas, Scikit-learn, Matplotlib for data manipulation, modeling, and visualization.
Google Colab: Used for executing code and managing computational resources.
