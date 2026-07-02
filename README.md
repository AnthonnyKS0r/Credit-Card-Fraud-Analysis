Credit Card Fraud Detection using Random Forest

A machine learning project for detecting fraudulent credit card transactions using a Random Forest Classifier. The notebook performs exploratory data analysis (EDA), data preprocessing, model training, and evaluation on a highly imbalanced fraud detection dataset.

Overview

Credit card fraud detection is a binary classification problem where the objective is to identify fraudulent transactions while minimizing false positives.

This project demonstrates a complete machine learning workflow, including:

Data exploration and statistical analysis
Fraud vs. legitimate transaction analysis
Correlation analysis
Data preprocessing
Train/test split
Random Forest model training
Performance evaluation
Confusion matrix visualization
Dataset

The project uses the well-known Credit Card Fraud Detection Dataset, which contains anonymized transaction features generated through PCA.

Dataset characteristics:

Transactions made by European cardholders
Highly imbalanced classes
Binary target:
0 → Legitimate transaction
1 → Fraudulent transaction

Note: The dataset (creditcard.csv) is not included in this repository due to its size. It can be downloaded from Kaggle.

Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Machine Learning Pipeline
Load and inspect the dataset
Perform exploratory data analysis (EDA)
Analyze class imbalance
Visualize feature correlations
Prepare features and labels
Split data into training and testing sets
Train a Random Forest classifier
Evaluate the model using multiple classification metrics
Visualize the confusion matrix
Evaluation Metrics

The model is evaluated using:

Accuracy
Precision
Recall
F1-score
Matthews Correlation Coefficient (MCC)
Confusion Matrix

These metrics provide a comprehensive evaluation, especially considering the severe class imbalance of fraud detection datasets.

Project Structure
.
├── Credit_Card_Fraud.ipynb
└── README.md
Running the Project

Clone the repository:

git clone https://github.com/your-username/your-repository.git
cd your-repository

Install the required libraries:

pip install numpy pandas matplotlib seaborn scikit-learn jupyter

Launch Jupyter Notebook:

jupyter notebook

Open:

Credit_Card_Fraud.ipynb
Results

The notebook trains a Random Forest Classifier to distinguish fraudulent transactions from legitimate ones and reports multiple evaluation metrics alongside a confusion matrix to assess the model's performance.

Future Improvements
Hyperparameter optimization using GridSearchCV or RandomizedSearchCV
Cross-validation
Feature importance analysis
ROC and Precision-Recall curves
Handling class imbalance with SMOTE or undersampling
Comparison with other models such as:
XGBoost
LightGBM
Logistic Regression
Support Vector Machines
Neural Networks
License

This project is intended for educational and research purposes.
