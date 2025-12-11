# Recommendation System with PySpark

This repository demonstrates how to **build and train a recommendation system model** using the **ALS (Alternating Least Squares)** algorithm with **PySpark**.

The project includes configuration notebooks and example workflows to help you understand how to work with Spark for recommendation tasks.

---

## 📌 Overview

Recommendation systems are widely used in modern data applications — from suggesting products to users on e-commerce platforms to recommending movies or content based on user preferences.

In this project, you will find:
- PySpark configurations and setup
- Logistic regression examples
- ALS-based collaborative filtering for building recommendation models

---

## 🚀 Files in This Repository

| File | Description |
|------|-------------|
| `spark_configuration.ipynb` | Set up and configure PySpark environment |
| `spark_logistic_regression.ipynb` | Example Python notebook showcasing a classification model using Spark |
| `spark_recommendation.ipynb` | Main notebook for building a recommendation system using ALS |

---

## 🛠️ Requirements

To run the notebooks, you will need:

- Python 3.x  
- Apache Spark  
- PySpark  
- Jupyter Notebook / JupyterLab  
- Optional: Databricks or any Spark-enabled environment

Install dependencies (example):

```bash
pip install pyspark
```

What You’ll Learn

✔ How to configure PySpark for local use
✔ How to build and evaluate simple ML models with Spark
✔ How to implement a collaborative filtering recommendation system using ALS
✔ How to load and preprocess data for Spark ML models

📎 References

ALS (Alternating Least Squares) is one of the most common matrix factorization techniques used in recommendation systems (implicit and explicit feedback).

This repo focuses on using PySpark’s MLlib implementation of ALS.

[Collaborative và content-based filtering](https://phamdinhkhanh.github.io/2019/11/04/Recommendation_Compound_Part1.html)
