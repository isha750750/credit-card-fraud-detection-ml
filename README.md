# credit-card-fraud-detection-ml
Detect fraudulent credit card transactions using Decision Tree and Random Forest models. Handles imbalanced data, visualizes class distribution, and compares model performance using metrics like accuracy, precision, recall, and F1-score.
Credit Card Fraud Detection Using Machine Learning

Problem Statement
With the rise of online transactions, credit card fraud has grown significantly. This project uses machine learning techniques to classify transactions as fraudulent or genuine.

Dataset
The dataset used is from [Kaggle's Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud), with 284,807 transactions and 492 fraud cases.

Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

 Models Used
- Decision Tree
- Random Forest

 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Results
| Model | Accuracy | Precision (Fraud) | Recall (Fraud) | F1-score |
|-------|----------|-------------------|----------------|----------|
| Decision Tree | 99.89% | 0.88 | 0.88 | 0.88 |
| Random Forest | 99.91% | 0.93 | 0.88 | 0.90 |

 Folder Structure


 credit-card-fraud-detection-ml/
│
├── creditcard.csv
├── fraud_detection.ipynb
├── README.md
└── model_comparison_report.txt

markdown
Copy
Edit

 How to Run
1. Clone the repo
2. Open the notebook
3. Upload `creditcard.csv`
4. Run all cells
