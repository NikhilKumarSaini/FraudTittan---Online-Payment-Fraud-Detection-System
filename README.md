# FraudTitan - Fraud Detection System

FraudTitan is a real-time fraud detection system built to help financial institutions, e-commerce platforms, and payment gateways detect and prevent fraudulent activities. The system leverages data science and machine learning to analyze transactional data and identify patterns associated with fraud.

## Project Overview

This project uses a dataset from [Kaggle](https://www.kaggle.com/datasets/jainilcoder/online-payment-fraud-detection/data) to build and evaluate models for detecting online payment fraud. The system analyzes transactions to determine the probability of fraud based on various transaction characteristics, such as the transaction amount, time, location, and device information.

### Dataset

- **Source**: [Online Payment Fraud Detection](https://www.kaggle.com/datasets/jainilcoder/online-payment-fraud-detection/data)
- **Description**: The dataset consists of multiple features, including customer and transaction details, and labels indicating whether a transaction was fraudulent.

### Methodology

1. **Data Preprocessing**: 
   - The data was cleaned and preprocessed to handle missing values, outliers, and categorical variables.
   - Exploratory Data Analysis (EDA) was conducted to understand feature distributions and correlations.

2. **Feature Engineering**:
   - New features were derived from existing ones to capture transaction behavior and customer patterns.
   - Important features like `transaction_amount`, `location_data`, and `device_info` were transformed to improve model accuracy.

3. **Model Training**:
   - Several machine learning models were trained to classify transactions as fraudulent or non-fraudulent, including Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.
   - Hyperparameter tuning was performed to optimize model performance, using techniques such as Grid Search and Cross-Validation.

4. **Evaluation Metrics**:
   - Models were evaluated using metrics like Precision, Recall, F1-Score, and Area Under the ROC Curve (AUC).
   - The final model chosen demonstrated a strong ability to distinguish between fraudulent and legitimate transactions.

5. **Deployment Plan**:
   - The project outlines steps for deploying the fraud detection model, including how it can be integrated with real-time data sources.
   - Plans for continuous model monitoring and retraining are included to adapt to new fraud patterns.

### Features

- **Automated Fraud Alerts**: The system sends real-time alerts for high-risk transactions.
- **Risk Scoring**: A risk score is assigned to each transaction, helping prioritize investigations.
- **Behavioral Analysis**: The system analyzes customer transaction history to detect unusual activity.
- **Comprehensive Reporting**: Generates reports on fraud trends and system performance.

### Technologies Used

- **Python**: For data analysis, preprocessing, and model development.
- **Pandas & Numpy**: Data manipulation and analysis.
- **Scikit-Learn**: Machine learning algorithms and model evaluation.
- **Matplotlib & Seaborn**: Data visualization.
- **Jupyter Notebook**: For interactive analysis and experimentation.

### Usage

FraudTitan can be used by financial and e-commerce institutions as part of their fraud prevention toolkit. With further integration, it can operate in real-time, providing risk assessments and transaction evaluations through a robust API.

### Repository Link

[GitHub Repository](https://github.com/NikhilKumarSaini/FraudTittan---Online-Payment-Fraud-Detection-System.git)

### Author

Developed by Nikhil Kumar Saini as part of a final-year BTech project.

### Acknowledgments

Special thanks to [JainilCoder](https://www.kaggle.com/jainilcoder) for providing the dataset on Kaggle.
