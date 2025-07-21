# 🩺 Diabetes Risk Factors – Data Analysis & Visualization Project

This project explores the relationship between key health indicators and diabetes diagnosis using a real-world dataset of 100,000 patients. It combines exploratory data analysis, data cleaning, predictive modeling, and interactive visualizations in Tableau to uncover meaningful health insights.

Viz - https://public.tableau.com/app/profile/meghana.patil2249/viz/DiabetesRiskFactors_17530624785200/Dashboard1
---

## 📌 Objectives

- Analyze how demographic, lifestyle, and health indicators influence diabetes
- Identify key predictors (like HbA1c level, BMI, blood glucose)
- Visualize trends using Tableau to communicate insights clearly
- Build a logistic regression model for diabetes prediction

---

## 📊 Dataset

- 📂 **Source**: [Kaggle – Diabetes Prediction Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset)
- 📈 **Size**: 100,000 patient records
- 🧪 **Features**:
  - `age`, `gender`, `bmi`, `HbA1c_level`, `blood_glucose_level`
  - `hypertension`, `heart_disease`, `smoking_history`
  - `diabetes` (target variable)

---

## 🧼 Data Preprocessing (Python in Google Colab)

- Encoded categorical features (`gender`, `smoking_history`)
- Created grouped fields:
  - `age_group` (Teen, Adult, Middle Age, Senior)
  - `bmi_group` (Underweight, Normal, Overweight, Obese)
- Removed missing/null values (none found)

---

## 🧠 Key Insights

| Factor         | Finding |
|----------------|---------|
| **HbA1c Level** | Strongest predictor of diabetes |
| **BMI**         | Higher BMI linked to higher diabetes prevalence |
| **Age**         | Middle-aged and senior individuals at higher risk |
| **Smoking**     | Current/former smokers more likely to be diabetic |

---

## 📈 Tableau Visualizations

🖼️ [Link to Tableau Public Dashboard (insert your link here)]()

### Visuals Included:
1. **Bar Chart** – Diabetes Distribution by Age Group
2. **Box Plot** – HbA1c Level by Diabetes Status
3. **Heatmap** – Average HbA1c, BMI, Glucose, and Age by Diabetes
4. **Pie Chart** – Smoking History Distribution (Diabetic Patients)

---

## 🤖 Predictive Modeling (Python)

- Model: **Logistic Regression**
- Accuracy: **96%**
- Most important features:
  - `HbA1c_level`
  - `hypertension`
  - `heart_disease`
  - `BMI`

---

## 🧰 Tech Stack

- **Python** (Pandas, Seaborn, Scikit-learn)
- **Tableau Public**
- **Google Colab**
- **GitHub**

---

## 🧑‍💼 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-risk-analysis.git
