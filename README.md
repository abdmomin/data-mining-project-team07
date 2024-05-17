# Data Mining Project - Team 7
Customer Churn Classification

## About the project
**Dataset Description:**
The Telco Customer Churn dataset, sourced from Kaggle, comprises 7,043 instances with 21 attributes each. The dataset is designed to facilitate the analysis of customer churn within a telecommunications company. Each instance represents a unique customer profile, with features encompassing demographic information, account details, service subscriptions, and tenure.
 
**Source:** https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data

1. **Data Preprocessing and Cleaning:**
* Load the Telco Customer Churn dataset using pandas.
* Perform exploratory data analysis (EDA) to understand the dataset's structure,   distribution, and relationships between variables.
* Handle missing values, if any, using appropriate techniques such as imputation or deletion.
* Encode categorical variables using one-hot encoding or label encoding as necessary.
* Split the dataset into training and testing sets to facilitate model evaluation.
 
2. **Data Visualization:**
* Utilize matplotlib to visualize key aspects of the dataset such as distributions of numerical features, class distributions, and correlations between variables.
* Generate histograms, bar plots, and scatter plots to gain insights into the data.
 
3. **Model Training:**
* Implement various classification algorithms including Logistic Regression, Support Vector Machines (SVM), Decision Tree, Random Forest, K-Nearest Neighbors (KNN), and similar models using Python libraries such as scikit-learn.
* Fit each model to the training data and evaluate their performance using appropriate metrics such as accuracy and F1-score.
 
4. **Hyperparameter Tuning:**
* Perform hyperparameter tuning using techniques like cross-validation and grid search to optimize model performance.
* Utilize cross-validation to assess model performance across different subsets of the training data and prevent overfitting.
* Use grid search to systematically explore different combinations of hyperparameters and identify the optimal set for each model.
 
5. **Error Analysis:**
* Analyze the errors made by each model to identify patterns and potential areas for improvement.
* Investigate misclassified instances and examine their characteristics to gain insights into the limitations of the models.
 
6. **Model Evaluation:**
* Evaluate the trained models using both accuracy score and F1-score to assess their overall performance.
* Compare the performance of different models and select the best-performing one based on the evaluation metrics.
* Consider the trade-offs between model complexity, interpretability, and performance when making the final selection.
