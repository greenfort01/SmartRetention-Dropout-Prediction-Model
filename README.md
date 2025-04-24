# Student Dropout Prediction Using Machine Learning Models

This project aims to predict whether a student is likely to drop out or graduate based on a rich dataset containing demographic, socioeconomic, macroeconomic, and academic features. Early identification of at-risk students allows educational institutions to take timely and targeted interventions.

## 📌 Project Objective

To develop and evaluate machine learning models that predict student dropout status using historical data. The ultimate goal is to provide actionable insights to academic institutions for reducing dropout rates.

---

## 📊 Dataset Description

- **Total records**: 4424 students  
- **Attributes**: 35 (demographic, socioeconomic, academic, etc.)
- **Target classes**:  
  - `0` = Dropout  
  - `1` = Graduate  

Data spans from 2008/2009 to 2018/2019 and includes students from 17 undergraduate programs.

---

## ⚙️ Tools & Libraries

- Python 3  
- pandas, NumPy, matplotlib, seaborn  
- scikit-learn  

---

## 📌 Data Preprocessing Steps

- Dropped irrelevant class `Enrolled` to focus on binary classification.
- Label encoding for categorical features.
- Standard scaling for normalization.
- Train-test split: **80% training / 20% testing**

---

## 🤖 Machine Learning Models Used

| Model               | Accuracy |
|--------------------|----------|
| Naive Bayes        | 85%      |
| Logistic Regression| 91%      |
| Random Forest      | 92%      |
| Support Vector Machine | 92% |
| Perceptron         | 89%      |
| K-Nearest Neighbors| 86%      |

> **Best Performing Models**:  
> ✅ **Random Forest**, **Support Vector Classifier**, and **Logistic Regression**

---

## 📈 Evaluation Metrics

All models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 🔍 Results and Discussion

While all models performed well, Random Forest and SVM showed the highest accuracy at **92%**. These models are suitable for identifying students at risk of dropping out. The model can help institutions reduce dropout rates through early interventions.

---

## 📌 Future Improvements

- Use advanced models like Gradient Boosting, XGBoost, or Deep Learning.
- Integrate real-time student data.
- Explore ensemble methods.
- Expand the dataset with behavioral or psychological attributes.

---

## 👨‍💻 Author

**Ayush Kumar**  
Email: ayushkumar46478@gmail.com
