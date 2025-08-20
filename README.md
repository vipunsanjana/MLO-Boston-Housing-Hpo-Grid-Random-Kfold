
# 🏡 Boston Housing Hyperparameter Optimization

This project demonstrates **Hyperparameter Optimization** for regression models using the **Boston Housing dataset**.
We compare **Lasso, Ridge, and ElasticNet Regression** with **Grid Search** and **Random Search** techniques, and evaluate model performance using **Root Mean Squared Error (RMSE)**.

---

## 📌 Features

* Apply **Lasso, Ridge, ElasticNet Regression**
* Perform **Hyperparameter Optimization** using:

  * Grid Search (exhaustive search)
  * Random Search (random sampling)
* Evaluate with:

  * Root Mean Squared Error (RMSE)
  * K-Fold Cross Validation

---

## 📂 Project Structure

```
MLO-Boston-Housing-Hpo-Grid-Random-Kfold/
│── MLO-Hyperparameter-Tuning.ipynb   # Main Python script with models and optimization
│── data/
│    └── Boston.CSV            # Dataset file
│── requirements.txt           # Dependencies
│── README.md                  # Documentation
```

---

## ⚙️ Installation

```bash
# Clone repository
git clone https://github.com/vipunsanjana/MLO-Boston-Housing-Hpo-Grid-Random.git
cd MLO-Boston-Housing-Hpo-Grid-Random

# Install dependencies
pip install -r requirements.txt
```

---

## 🚀 Usage

Open the Jupyter Notebook to run and explore the models:

```bash
# Launch Jupyter Notebook
jupyter notebook

# Then open:
MLO-Hyperparameter-Tuning.ipynb
```

The script will:

* Run Grid Search & Random Search on **Lasso Regression**
* Train Ridge and ElasticNet with chosen hyperparameters
* Print RMSE scores for all models

---

## 📊 Example Output

```
Best Lasso alpha (Grid Search): 0.1
Best Lasso alpha (Random Search): 0.1

Lasso RMSE: 6.02
ElasticNet RMSE: 6.04
Ridge RMSE: 5.85
```

---

## 📚 Learnings

* **Grid Search** tries all parameter combinations (accurate but slow)
* **Random Search** samples a subset (faster, resource-efficient)
* **Lasso** can shrink some coefficients to zero → feature selection
* **Ridge** reduces overfitting with coefficient shrinkage
* **ElasticNet** balances Ridge and Lasso effects

---

## 🛠️ Tech Stack

* Python 3.x
* pandas, numpy
* scikit-learn

---

## 👨‍💻 Author

**Vipun Sanjana**
*Software Engineer | Full Stack | ML & DevOps*

---
