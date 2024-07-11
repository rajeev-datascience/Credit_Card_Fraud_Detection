#Credit Card Fraud Detection

Project Overview

Credit card fraud is a significant issue in the financial sector, leading to substantial financial losses. This project aims to build and evaluate various machine learning models to detect fraudulent credit card transactions. The highly imbalanced nature of the dataset necessitates the use of various data balancing techniques to improve model performance.

Project Structure

The project is organized into several key sections:

1.	Data Loading and Preprocessing:
o	Loading the dataset.
o	Handling missing values and encoding categorical variables.
o	Normalizing features for consistent model performance.

2.	Exploratory Data Analysis (EDA):
o	Visualizing class distribution.
o	Analyzing feature correlations.
o	Identifying and handling outliers.
o	Plotting feature distributions and relationships.

3.	Data Balancing Techniques:
o	Applying under-sampling to the majority class.
o	Using SMOTE (Synthetic Minority Over-sampling Technique) for over-sampling.
o	Implementing ADASYN (Adaptive Synthetic Sampling) for over-sampling.
o	Exploring combined sampling methods for improved balance.

4.	Model Training and Evaluation:
o	Training models including Logistic Regression, Decision Tree, and Random Forest.
o	Evaluating models using confusion matrices, classification reports, and additional metrics like AUC-ROC.

5.	Comparison and Insights:
o	Summarizing and comparing model results using various performance metrics.
o	Visualizing model comparisons.

Data

The dataset used in this project is from the Kaggle Credit Card Fraud Detection competition. It contains transactions made by credit cards in September 2013 by European cardholders.

•	Number of transactions: 284,807
•	Number of fraudulent transactions: 492
•	Features: 30 (including Time, Amount, and 28 anonymized features V1 to V28)

Modeling Techniques

1.	Logistic Regression:
o	Basic model with different sampling techniques.

3.	Decision Tree:
o	Basic model with different sampling techniques.

5.	Random Forest:
o	Basic model with different sampling techniques.

Evaluation Metrics

•	Confusion Matrix
•	Classification Report (Precision, Recall, F1-Score)

Results and Insights

•	Detailed performance metrics for each model and sampling technique.
•	Visual comparison of models using bar plots for accuracy, precision, recall, F1-Score, and ROC AUC.
•	Insights into the effectiveness of different data balancing techniques and model combinations.

