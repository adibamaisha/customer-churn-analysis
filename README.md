# Customer Churn Prediction

End-to-end machine learning project predicting customer churn with 84.3% ROC-AUC.

---

## 🛠️ Skills & Tools

| Category | Tools |
|----------|-------|
| **Data Prep** | Excel (cleaning, encoding, one-hot) |
| **EDA** | Excel (pivot tables, charts) |
| **ML Models** | Python, scikit-learn |
| **Algorithms** | Logistic Regression, Decision Tree, Random Forest, Gradient Boosting |
| **Evaluation** | ROC-AUC, F1-Score, Confusion Matrix, Cross-Validation |
| **Visualization** | Matplotlib, Seaborn |
| **Version Control** | Git, GitHub |

---

## 📊 Results

| Metric | Score |
|--------|-------|
| Accuracy | 76.2% |
| Recall | 77.8% |
| F1-Score | 63.5% |
| ROC-AUC | 84.3% |

**Best Model**: Random Forest

---

## 🔍 Key Insights

- Month-to-month contracts = highest churn risk (17.1% importance)
- Short tenure = second strongest predictor (12.6%)
- Tech support = significant retention factor (6.9%)

---

## 📁 Project Structure

├── data/ # Dataset
├── notebooks/ # Jupyter notebook
├── models/ # Saved model (.pkl)
├── reports/ # Results & visuals
├── Churn_Analysis_Report.pdf
└── requirements.txt # Dependencies
## 🚀 Quick Start

```bash
pip install -r requirements.txt
jupyter notebook
