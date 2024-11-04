# FraudTitan - Fraud Detection System

FraudTitan is a real-time fraud detection system built to help financial institutions, e-commerce platforms, and payment gateways detect and prevent fraudulent activities. This project employs data science and machine learning techniques to classify online payment transactions as fraudulent or non-fraudulent.

## Project Overview

This project uses a dataset from [Kaggle](https://www.kaggle.com/datasets/jainilcoder/online-payment-fraud-detection/data) to train a model for detecting fraudulent transactions. The analysis includes data preprocessing, correlation analysis, and training a simple Decision Tree model to predict the likelihood of fraud.

### Dataset

- **Source**: [Online Payment Fraud Detection](https://www.kaggle.com/datasets/jainilcoder/online-payment-fraud-detection/data)
- **Description**: This dataset includes transaction details, such as transaction type, amount, old and new balances, and labels indicating whether a transaction was fraudulent.

### Methodology

1. **Exploratory Data Analysis (EDA)**:
   - Visualized the distribution of fraud and non-fraud transactions using pie charts and bar charts.
   - Generated a heatmap to examine the relationship between transaction types and fraud status.

2. **Correlation Analysis**:
   - Calculated the correlation between various features and fraud status to identify the most influential features.
   - Plotted a correlation heatmap for numerical features, highlighting key relationships.

3. **Machine Learning Model**:
   - **Model**: Used a `DecisionTreeClassifier` as the primary model for fraud prediction.
   - **Training**: Split the data into training and testing sets (80-20) to train and validate the model.
   - **Evaluation**: The model’s accuracy was measured on the test set to gauge its performance.

4. **Prediction Example**:
   - Used the trained model to predict fraud on a sample transaction with features `[type, amount, oldbalanceOrg, newbalanceOrig]`.
   - For example, a transaction with features `[4, 9000.60, 9000.60, 0.0]` was classified by the model to determine its fraud status.

### Key Visualizations

- **Fraud vs. Non-Fraud Distribution**: Pie and bar charts showing the proportion of fraudulent and legitimate transactions.
- **Transaction Type vs. Fraud Status**: Heatmap visualizing correlations between transaction types and fraud indicators.
- **Feature Correlation Heatmap**: Heatmap of correlations among numeric features to identify relationships impacting fraud detection.

### Technologies Used

- **Python**: For data analysis and model development.
- **Pandas & Numpy**: Data handling and manipulation.
- **Scikit-Learn**: For training the Decision Tree model.
- **Matplotlib & Seaborn**: Data visualization.
- **Jupyter Notebook**: For interactive analysis and project development.

### Usage

FraudTitan provides a foundational model that can be further refined and integrated into a real-time fraud detection system, suitable for institutions that need basic, interpretable fraud detection capabilities.

### Repository Link

[GitHub Repository](https://github.com/NikhilKumarSaini/FraudTittan---Online-Payment-Fraud-Detection-System.git)

### Author

Developed by Nikhil Kumar Saini as part of a final-year BTech project.

### Acknowledgments

Special thanks to [JainilCoder](https://www.kaggle.com/jainilcoder) for providing the dataset on Kaggle.
