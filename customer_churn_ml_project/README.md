# 📊 Customer Churn Prediction – ML Portfolio Project

This is a **Python machine learning / data science project** built to be shared on GitHub.

It includes:

- A complete **Jupyter Notebook**: `customer_churn_ml.ipynb`
- A simple `requirements.txt` for reproducibility

The notebook walks through an end-to-end churn prediction workflow:

1. **Synthetic dataset creation** using `scikit-learn.make_classification`
2. **Exploratory Data Analysis (EDA)** with:
   - Summary statistics
   - Histograms
   - Churn rate vs. binned features
3. **Train/test split**
4. **Modeling**:
   - Logistic Regression (baseline)
   - Random Forest (tree-based model)
5. **Evaluation**:
   - Accuracy
   - Classification report
   - Confusion matrix plot
   - Model comparison bar chart
6. **Feature importance** visualization for the Random Forest model

---

## 🧠 Tech Stack

- Python
- Jupyter Notebook
- NumPy
- pandas
- matplotlib
- scikit-learn

---

## ▶️ How to Run

1. Create and activate a virtual environment (optional but recommended):

```bash
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Launch Jupyter:

```bash
jupyter notebook
```

4. Open `customer_churn_ml.ipynb` from the Jupyter interface and run the cells from top to bottom.

---

## 📂 Project Structure

```text
customer_churn_ml_project/
├─ customer_churn_ml.ipynb   # Main notebook
├─ requirements.txt          # Dependencies
└─ README.md                 # Project description (this file)
```

---

## 🌟 Why this is portfolio-ready

This project demonstrates that you can:

- Set up a reproducible **Python data science environment**
- Perform **EDA** and create clear visualizations
- Train and compare **ML models**
- Communicate results with plots and structured analysis

You can easily extend it later with:
- ROC curves / AUC metrics
- Cross-validation
- Hyperparameter tuning
- Saving models with `joblib`
