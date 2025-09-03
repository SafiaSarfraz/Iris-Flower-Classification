# 🌼 Iris Flower Classification

## 📌 Project Overview
This project uses the classic **Iris dataset** to classify flowers into three species:  
- Setosa  
- Versicolor  
- Virginica  

The classification is based on features such as **sepal length, sepal width, petal length, and petal width**.  
The project demonstrates a full machine learning workflow: **data preprocessing, model training, evaluation, and visualization**.

---

## 🔑 Workflow

1. **Data Loading**
   - Used the built-in `load_iris` dataset from `scikit-learn`.
   - Converted to a pandas DataFrame for easier handling.

2. **Exploratory Data Analysis (EDA)**
   - Summary statistics of all features.
   - Pairplots to visualize feature relationships by species.
   - Identified that **petal length and width** provide the clearest separation.

3. **Preprocessing**
   - Standardized features using `StandardScaler` to normalize input data.

4. **Model Training**
   - **Logistic Regression** as the baseline classifier.
   - Compared with **KNN, Random Forest, and SVM**.

5. **Evaluation**
   - Accuracy score  
   - Classification report (precision, recall, F1-score)  
   - Confusion matrix heatmap for visual comparison of predicted vs actual classes.

---

## 📊 Results

| Model              | Accuracy |
|--------------------|----------|
| Logistic Regression | ~97–100% |
| KNN                 | ~96–98% |
| Random Forest       | ~97–100% |
| SVM                 | ~97–100% |

✅ All models achieved very high accuracy because the dataset is clean and well-separated.  
✅ **Petal length and petal width** are the most influential features.  

---

## 🔍 Key Insights
- The Iris dataset is an excellent introduction to supervised learning.  
- Even simple models like Logistic Regression can achieve near-perfect accuracy.  
- Feature scaling helps algorithms like Logistic Regression and SVM perform optimally.  
- Confusion matrices show that most misclassifications occur between **Versicolor and Virginica**, as they are more similar.  

---

## ⚙️ Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Scikit-learn  
- Seaborn, Matplotlib  

---
📌 Conclusion

This project shows how to build a complete machine learning pipeline for classification.
It demonstrates the importance of EDA, feature scaling, model evaluation, and visualization.

With simple preprocessing and classical models, the Iris dataset can be classified with over 97% accuracy.
