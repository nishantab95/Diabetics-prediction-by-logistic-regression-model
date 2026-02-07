🩺 Diabetes Prediction using Machine Learning

This project builds an end-to-end machine learning pipeline to predict the likelihood of diabetes based on medical attributes such as glucose level, BMI, blood pressure, and age. The workflow includes data cleaning, exploratory data analysis (EDA), feature scaling, handling class imbalance, model training using Logistic Regression, and performance evaluation.

📌 Project Overview

Problem Type: Binary Classification (Diabetes: Yes/No)

Algorithm Used: Logistic Regression

Key Steps:

Data loading and cleaning

Handling missing values and outliers

Exploratory Data Analysis (EDA)

Feature scaling (MinMax/Standard Scaler)

Train-test split

Model training and evaluation

Comparison of different decision thresholds

📊 Results (Final Model)

Accuracy: ~75–78%

Recall (Diabetic class): ~0.55–0.66

F1-score (Diabetic class): ~0.59–0.60

Since the dataset is imbalanced, evaluation focuses on recall and F1-score for the positive (diabetic) class rather than accuracy alone.

🧠 Key Learnings

Accuracy alone is misleading for imbalanced datasets.

There is a trade-off between precision and recall when tuning classification thresholds.

Proper feature scaling and handling class imbalance significantly affect model performance.

🛠️ Tech Stack

Language: Python

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Environment: Jupyter Notebook / Kaggle

📁 Repository Structure
├── data/
│   └── diabetes.csv
├── notebooks/
│   └── diabetes_prediction.ipynb
├── README.md

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/diabetes-prediction-ml.git


Install dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn


Open the notebook:

jupyter notebook


Run diabetes_prediction.ipynb

📈 Future Improvements

Try tree-based models (Random Forest, XGBoost)

Perform hyperparameter tuning with cross-validation

Improve recall for the diabetic class

Add ROC-AUC and PR-AUC evaluation

🙌 Acknowledgements

Dataset source: Kaggle (Diabetes Dataset)

Inspired by real-world healthcare screening use-cases
