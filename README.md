# 🎓 Student Dropout Prediction

A machine learning project to predict whether a student will **drop out**, remain **enrolled**, or **graduate**, based on academic performance and demographic data.

## 📊 Dataset

- **Source**: [Unnamed Portuguese Higher Education Institute]([https://archive.ics.uci.edu/dataset/697](https://www.kaggle.com/datasets/adilshamim8/predict-students-dropout-and-academic-success/data))
- **Records**: Student's personal, academic and some external data.
- **Target Classes**: `Dropout`, `Enrolled`, `Graduate`

## 🧠 Problem Statement

Educational institutions face challenges in identifying students at risk of dropping out. This project builds a classification model to predict student outcomes and assist in early intervention.

---

## 🔧 Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Random Forest Classifier
- GridSearchCV for hyperparameter tuning
- Evaluation metrics: Confusion Matrix, Accuracy, Cross-Validation

---

## 📈 Workflow

1. **Exploratory Data Analysis (EDA)**
2. **Feature Engineering**
   - Derived metrics: Approval rates, grade averages, etc.
   - Feature selection using importance scores
3. **Model Training**
   - Grid search to optimize hyperparameters (`n_estimators`, `max_depth`, `min_samples_split`, etc.)
   - Training on the top 20 most important features
4. **Evaluation**
   - **Test Accuracy**: **76.6%**
   - **Cross-Validation Accuracy**: **77.4%**
   - Analysis using a confusion matrix for class-wise performance

---

## 📌 Results

| Metric         | Score     |
|----------------|-----------|
| Test Accuracy  | 76.6%     |
| CV Accuracy    | 77.4%     |
| Best Model     | Random Forest (Tuned) |

### Confusion Matrix (Test Set)

```
[[237  28  51]
 [ 37  51  63]
 [ 11  17 390]]
```

---

## 🚀 Future Improvements

- Experiment with ensemble methods (Voting, Stacking)
- Investigate feature explanations using SHAP
- Deploy the model with a Streamlit dashboard for real-time predictions

---

## 🧑‍💻 Author

**Siddharth Mahajan**  
