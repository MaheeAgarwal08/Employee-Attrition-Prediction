# 💼 Employee Attrition Prediction

This machine learning project predicts whether an employee is likely to leave the company using a Random Forest Classifier. The model was built with Python and trained on real-world HR data.

---

## 📊 Dataset
- **Source**: `Dataset01-Employee_Attrition.csv`
- **Size**: 14,999 records
- **Features**:
  - `satisfaction_level`
  - `last_evaluation`
  - `number_project`
  - `average_monthly_hours`
  - `time_spend_company`
  - `Work_accident`
  - `promotion_last_5years`
  - `salary`
  - `Department`
  - `left` (Target)

---

## ⚙️ Workflow
- Data Preprocessing & Cleaning
- EDA: Histograms, Boxplots, Crosstabs
- Label Encoding (for `salary` and `Department`)
- Train-Test Split & Standardization
- Model Training using **Random Forest Classifier**
- Evaluation using:
  - Confusion Matrix
  - Accuracy & Precision
  - Classification Report
- Feature Importance Plot
- 5-Fold Cross-Validation

---

## 📈 Results
- **Accuracy**: ~90%
- Feature Importance revealed `satisfaction_level` and `time_spend_company` as key predictors.

---

## 🧰 Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab

---


