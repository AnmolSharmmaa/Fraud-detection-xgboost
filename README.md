
# 🛡️ Fraud Detection System using XGBoost

This project is a Machine Learning solution for detecting fraudulent financial transactions using a large-scale synthetic dataset (~6.3 million records). The objective is to build a high-performing fraud detection model and provide business insights and prevention strategies.

---

## 📌 Overview

- ✅ Cleaned and preprocessed real-world simulated data
- ✅ Handled class imbalance using SMOTE
- ✅ Engineered features for better fraud pattern detection
- ✅ Built and evaluated a robust XGBoost model
- ✅ Visualized feature importance and interpreted results
- ✅ Suggested infrastructure prevention methods & impact evaluation

---

## 📁 Project Structure

-Fraud_Detection.ipynb # Jupyter Notebook with full project
-requirements.txt # Python dependencies
-README.md 

> 📂 **Note:** Dataset (`Fraud.csv`) is not included due to size. Add your own copy in the working directory.

---

## 🧰 Tech Stack

- Python 3.8+
- Pandas, NumPy
- Scikit-learn
- XGBoost
- imbalanced-learn (SMOTE)
- Matplotlib & Seaborn

---

## 🔍 Key Features

- Data cleaning (missing values, outliers, irrelevant features)
- One-hot encoding for transaction type
- Feature engineering (`balance_diff`, `amount`, `type`)
- SMOTE for class balancing
- XGBoost Classifier with hyperparameter tuning
- Model evaluation using precision, recall, F1-score, ROC-AUC
- Feature importance plot
- Business recommendations and action monitoring strategies

---

## 📈 Performance

| Metric       | Score     |
|--------------|-----------|
| ROC AUC      | ~0.98     |
| Recall       | High      |
| Precision    | Balanced  |
| Model Used   | XGBoost   |

---

## 🚀 How to Run


1. Clone the repository  
```bash
git clone https://github.com/yourusername/fraud-detection-xgboost.git
cd fraud-detection-xgboost
```  

2. Create virtual environment  
```bash
python -m venv venv
source venv/bin/activate
```  

3.Install dependencies
```bash
pip install -r requirements.txt
``` 

4.Run the notebook
```bash
jupyter notebook
``` 


## 🔒 Business Recommendations

- Enable real-time fraud monitoring  
- Use anomaly detection for unknown fraud patterns  
- Enforce dynamic transaction limits  
- Apply multi-factor authentication  
- Secure infrastructure with access control and encryption  

---

## ✅ Post-Deployment Evaluation

- Monitor fraud rates post-implementation  
- A/B test with legacy systems  
- Analyze false positive/negative trends  
- Measure customer satisfaction and complaints  

---

## 👨‍💻 Author

**Anmol Mudgal**  
[LinkedIn][https://linkedin.com/in/yourusername](https://www.linkedin.com/in/anmol-mudgal-a34109265/]

📧 anmolsharma8938@gmail.com


