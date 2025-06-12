# 📧 Spam Email Detection

A machine learning project to classify SMS messages as **Spam** or **Ham** (Not Spam) using **Natural Language Processing (NLP)** techniques and **Scikit-learn**. This binary classification task uses the **UCI SMS Spam Collection Dataset** and implements various models including Naive Bayes, SVM, and Logistic Regression with performance tuning.

---

## 🚀 Features

- Text preprocessing and cleaning
- Feature extraction using TF-IDF with n-grams
- Handling imbalanced classes using **SMOTE**
- Hyperparameter tuning with **GridSearchCV**
- Model comparison: Naive Bayes, SVM, Logistic Regression
- Save & load trained model and vectorizer
- Predict new SMS messages

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK (for stopword removal)
- Imbalanced-learn (for SMOTE)
- Matplotlib, Seaborn (for visualization)
- Joblib (for model persistence)
