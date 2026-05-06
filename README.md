# 🐍 Python Projects — ML Pipeline & Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=flat)
![Stars](https://img.shields.io/badge/Stars-2⭐-gold?style=flat)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat)

> 🛠️ A collection of Python projects covering **end-to-end ML pipelines,
> regression modeling, and interactive data analysis applications** —
> demonstrating practical Python skills from data processing to
> model deployment.

---

## 📁 Projects Overview

| File | Project | Key Concepts |
|------|---------|-------------|
| `DataAnalysisApp.py` | Interactive Data Analysis App | Pandas, file handling, analysis automation |
| `M2_DIY_AI_ML_Pipeline_Implementation_.ipynb` | End-to-End ML Pipeline | Preprocessing, training, evaluation pipeline |
| `Module4_DIY_Regression.ipynb` | DIY Regression Model | Linear regression from scratch + Scikit-learn |

---

## 🔍 Project Details

### 1. 📊 Data Analysis App (`DataAnalysisApp.py`)
A Python application for automated data analysis — load any CSV
and instantly get statistical summaries, distributions, and insights.

```python
# Run the app
python DataAnalysisApp.py
```

**Features:**
- Load and inspect any CSV dataset
- Automatic statistical summary (mean, std, min, max)
- Missing value detection and reporting
- Column-wise data type analysis
- Quick data profiling without manual EDA

---

### 2. 🤖 End-to-End ML Pipeline (`M2_DIY_AI_ML_Pipeline_Implementation_.ipynb`)
A complete ML pipeline built from scratch — demonstrating the
full workflow from raw data to trained model.

```
Raw Data
    ↓
Data Loading & Inspection
    ↓
Preprocessing (missing values, encoding, scaling)
    ↓
Train-Test Split
    ↓
Model Training
    ↓
Evaluation (Accuracy, F1, Confusion Matrix)
    ↓
Pipeline Object (reusable)
```

**Key Concepts:**
- Scikit-learn `Pipeline` object
- `ColumnTransformer` for mixed data types
- Model evaluation metrics
- Reusable, production-ready pipeline structure

---

### 3. 📈 DIY Regression (`Module4_DIY_Regression.ipynb`)
Regression modeling — both from scratch (pure math) and
using Scikit-learn, to understand what happens under the hood.

```python
# From scratch — understanding the math
def gradient_descent(X, y, lr=0.01, epochs=1000):
    m, b = 0, 0
    n = len(y)
    for _ in range(epochs):
        y_pred = m * X + b
        dm = (-2/n) * sum(X * (y - y_pred))
        db = (-2/n) * sum(y - y_pred)
        m -= lr * dm
        b -= lr * db
    return m, b

# Scikit-learn version
from sklearn.linear_model import LinearRegression
model = LinearRegression()
model.fit(X_train, y_train)
```

**Key Concepts:**
- Linear Regression math — MSE, gradient descent
- `sklearn.linear_model.LinearRegression`
- R² Score, MAE, RMSE evaluation
- Visualization of regression line

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Python 3.x |
| Data Processing | Pandas, NumPy |
| ML | Scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Notebooks | Jupyter Notebook |

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/tashfeen786/python-Projects.git
cd python-Projects

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Run Data Analysis App
python DataAnalysisApp.py

# Or open notebooks
jupyter notebook
```

---

## 🏗️ Project Structure

```
python-Projects/
│
├── DataAnalysisApp.py                          # Data analysis CLI app
├── M2_DIY_AI_ML_Pipeline_Implementation_.ipynb # Full ML pipeline
├── Module4_DIY_Regression.ipynb                # Regression from scratch
└── README.md
```

---

## 🔮 Future Additions

- [ ] Classification pipeline project
- [ ] Flask REST API for ML model serving
- [ ] Streamlit dashboard for DataAnalysisApp
- [ ] Time series analysis project

---

## 👨‍💻 Author

**Tashfeen Aziz** — AI/ML Engineer & Python Developer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/tashfeen-aziz-b51361292)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/tashfeen786)
[![Email](https://img.shields.io/badge/Email-Contact-red?logo=gmail)](mailto:tashfeen247@gmail.com)

---

⭐ **If you found this helpful, please give it a star!**
