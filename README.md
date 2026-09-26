# 🚗 Predictive Models & Applied Machine Learning

> **Advanced regression workflows, polynomial feature engineering, and rigorous residual analysis built in Python for real-world valuation and forecasting.**

---

## 🧰 Tech Stack & Tools

<div align="center" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 25px; padding: 20px 0;">
  <a href="https://www.python.org" target="_blank" title="Python"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="55" height="55" /></a>
  <a href="https://scikit-learn.org/" target="_blank" title="Scikit-learn"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" alt="Scikit-learn" width="55" height="55" /></a>
  <a href="https://pandas.pydata.org/" target="_blank" title="Pandas"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" alt="Pandas" width="55" height="55" /></a>
  <a href="https://numpy.org/" target="_blank" title="NumPy"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="NumPy" width="55" height="55" /></a>
  <a href="https://matplotlib.org/" target="_blank" title="Matplotlib"><img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" alt="Matplotlib" width="55" height="55" /></a>
  <a href="https://jupyter.org/" target="_blank" title="Jupyter Notebooks"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" alt="Jupyter" width="55" height="55" /></a>
  <a href="https://git-scm.com/" target="_blank" title="Git"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" width="55" height="55" /></a>
</div>

---

## 🎯 Overview & Use Case

Predicting physical-world values (such as used car valuation based on engine power, age, and mileage) requires moving beyond naive linear assumptions. This repository demonstrates the systematic evolution and iterative refinement of machine learning models—highlighting feature scaling, data cleansing mechanics, and the prevention of overfitting in predictive analytics.

---

## 📈 Included Models & Evolution

| Model / Notebook | Focus & Architecture | Performance / Key Takeaway |
| :--- | :--- | :--- |
| **1. Linear Regression** (`LinearRegression.ipynb`) | Baseline model establishing simple linear relationships between engine power and market price. | Establishes baseline error metrics and highlights the limits of linear assumptions. |
| **2. Polynomial Regression** (`PolynomialRegression.ipynb`) | Analysis of model complexity, demonstrating how higher-degree polynomials cause overfitting and numerical instability (Condition Number). | Emphasizes the importance of regularization and mathematical sanity checks. |
| **3. Multiple Regression** (`MultipleRegression.ipynb`) | **Final Production Model:** Multivariate Degree 2 Polynomial capturing non-linear depreciation curves. | **$R^2 = 0.76$** — High predictive accuracy with stable generalization for real-world inputs + interactive valuation widget. |

---

## 🛠️ Key Engineering Techniques

* **Systematic Data Cleaning:** Implemented the `6/3/2 Outlier Rule` to isolate anomalies and ensure data integrity.
* **Feature Scaling:** Applied `StandardScaler` for numerical stability across multi-variable polynomial expansions.
* **Residual Analysis:** Visual verification of model accuracy, error distribution, and heteroscedasticity checks.

---

## 📂 Repository Structure

```text
ml-predictive-models/
│
├── Linear Regression.ipynb         # Simple baseline regression workflow
├── Multiple Regression.ipynb       # Final multivariate model (Degree 2, R² = 0.76)
├── Polynomial Regression.ipynb     # Complexity analysis & overfitting prevention
├── cars_data.csv                   # Cleaned dataset for valuation training

