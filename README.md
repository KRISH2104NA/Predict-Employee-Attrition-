# 🚀 Predict Employee Attrition using Machine Learning

This project builds a classification model to predict whether an employee is likely to leave a company based on factors such as job satisfaction, salary, work environment, and years of experience.

---

## 📌 Problem Statement

Employee attrition has a significant impact on organizations. By predicting which employees are likely to leave, companies can take proactive steps to improve retention. This project leverages machine learning, specifically a Random Forest Classifier, to build a predictive model using HR data.

---

## 📊 Dataset

The dataset used is the **IBM HR Analytics Employee Attrition Dataset**.

| Feature | Description |
|--------|-------------|
| JobSatisfaction | Level of satisfaction with the job |
| MonthlyIncome | Employee's monthly salary |
| WorkEnvironment | Quality of the work environment |
| YearsAtCompany | Number of years the employee has been with the company |
| Attrition | Target variable (Yes/No) |

---

## 🧠 Model & Methodology

- **Preprocessing**:
  - Dropped irrelevant columns (`EmployeeCount`, `EmployeeNumber`, `StandardHours`, `Over18`)
  - Label encoded categorical features
  - Encoded `Attrition` column as binary (Yes = 1, No = 0)

- **Model**: Random Forest Classifier (`n_estimators=100`)

- **Evaluation**:
  - Confusion Matrix
  - Accuracy, Precision, Recall, F1-score
  - Heatmap for visualization
  - Feature importance plot

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib

---

## 📈 Results

- **Accuracy**: ~89%
- **Confusion Matrix**: Visualized using a heatmap
- **Top Features**: Determined using feature importance plot

---

## 🔍 Visualizations

### Confusion Matrix Heatmap

![Confusion Matrix](./images/confusion_matrix.png)

### Feature Importance

![Feature Importance](./images/feature_importance.png)

> Add these plots under a folder named `images` in your repo.

---

## 📁 File Structure

