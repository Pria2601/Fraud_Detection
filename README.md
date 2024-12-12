# Fraud_Detection
This project focuses on identifying fraudulent transactions by building a reliable machine learning solution. It combines effective data preparation techniques with powerful classification models to deliver robust results.

## Overview
Using a dataset of financial transactions, this system trains machine learning models to differentiate between legitimate and fraudulent activities. The project ensures reliability through rigorous evaluation and optimization strategies.

## Key Features
- **Data Handling**: Balanced the dataset using SMOTE to address class imbalances and prepared it for training and testing.
- **Model Training**: Built and fine-tuned models such as Logistic Regression and XGBoost for classification.
- **Performance Analysis**: Evaluated models with key metrics like Accuracy, F1-Score, and ROC-AUC to ensure dependable predictions.

## Dataset
- **Source**: The dataset used is `https://drive.google.com/file/d/1ipKhvkz0QPARIpaKL88WP79fYCVRlwN2/view?usp=drive_link`.
- **Description**: Includes transactional data labeled to indicate whether each transaction is fraudulent or legitimate.

## Technologies and Tools
- **Programming Language**: Python
- **Libraries and Tools**: 
  - Data Processing: NumPy, Pandas
  - Visualization: Matplotlib
  - Machine Learning: Scikit-learn, XGBoost
  - Data Balancing: SMOTE

## How to Run the Project
1. Clone this repository.
2. Install required libraries with:
   ```bash
   pip install -r requirements.txt
   ```
3. Place the dataset naming (`PS_20174392719_1491204439457_log.csv`) in the project folder.
4. Execute the main script to train and evaluate models:
   ```bash
   python main.py
   ```

## Performance Metrics
- **Accuracy**: The percentage of correctly identified transactions.
- **F1-Score**: A metric balancing precision and recall, ideal for imbalanced datasets.
- **ROC-AUC**: Measures the model's ability to distinguish between classes.

## Results
The trained models achieved excellent results, showcasing their ability to identify fraudulent transactions accurately and reliably.


---
Your feedback and contributions are welcome to make this system even better.
