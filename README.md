# 🛸 Spaceship Titanic – Classification Challenge

Predict which passengers on the **Spaceship Titanic** were transported to another dimension.  

---

## 📚 Resources
Datasets: [Kaggle competition](https://www.kaggle.com/competitions/spaceship-titanic/overview).

---

## 📊 Approach Overview
- **Data Understanding:** Checked missing values, visualized distributions (histogram, boxplot), correlation heatmaps.  
- **Feature Engineering:** Split `Cabin`, extract `Group` from `PassengerId`, encode categorical features, create `TotalSpend`.  
- **Modeling:** Logistic Regression, RandomForest, XGBoost/LightGBM with cross-validation.  
- **Submission:** Predictions formatted as `PassengerId,Transported`.  

---

## 📈 Results
| Model              | CV Accuracy |
|--------------------|-------------|
| LogisticRegression | 0.78        |
| RandomForest       | 0.80        |
| XGBoost (final)    | 0.81        |

---

## 🧰 Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)  
![NumPy](https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)  
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)  
![Seaborn](https://img.shields.io/badge/seaborn-2E4053?style=for-the-badge&logo=seaborn&logoColor=white)  
![Matplotlib](https://img.shields.io/badge/matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)  
![XGBoost](https://img.shields.io/badge/XGBoost-EB5E28?style=for-the-badge&logo=xgboost&logoColor=white)  
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)  

