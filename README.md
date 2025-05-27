# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project is part of the AI & ML Internship Task 2 and involves performing Exploratory Data Analysis (EDA) on the Titanic dataset to uncover hidden patterns and insights using Python libraries like Pandas, Matplotlib, and Seaborn.

---

## 📌 Objective

To analyze the Titanic dataset by:
- Generating descriptive statistics.
- Creating visualizations (histograms, boxplots, pairplots).
- Understanding relationships between features.
- Extracting meaningful insights.

---

## 🛠 Tools & Libraries Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📁 Dataset

The dataset used is a cleaned version of the original Titanic dataset with one-hot encoded columns for categorical features.

**Columns include**:
- `PassengerId`, `Survived`, `Pclass`, `Name`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`
- Encoded: `Sex_male`, `Embarked_Q`, `Embarked_S`

---

## 📊 Key Steps Performed

1. **Loading & Inspecting Data**
   - Checked dataset shape, info, and missing values.
   - Verified column names.

2. **Descriptive Statistics**
   - Used `describe()` for summary stats.
   - Assessed distributions and central tendencies.

3. **Visualization**
   - **Histograms** and **Boxplots** for age, fare, etc.
   - **Countplots** for survival by sex and class.
   - **Heatmap** for feature correlation.
   - **KDE plots** for age distribution by survival.

4. **Feature Engineering**
   - Converted `Sex_male` to human-readable `Sex` labels for visualization.

5. **Insights Extracted**
   - Higher survival rate among **females**.
   - Passengers in **1st class** had a higher chance of survival.
   - Children and younger passengers were more likely to survive.
   - Slightly higher fare correlated with increased survival odds.

---

## ✅ Deliverables

- `Task2.ipynb` - The main analysis notebook.
- `Cleaned_Titanic.csv` - Dataset used for the analysis.
- `README.md` - This file.


---

## 💬 Interview Prep Questions

- What is the purpose of EDA?
- How do boxplots help in understanding a dataset?
- What is correlation and why is it useful?
- What is multicollinearity?
- How can skewness be detected?
- How has EDA helped you in previous projects?

---

## 🙌 Acknowledgments

Dataset Source: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)  
Inspired by: AI & ML Internship Task 2 Guidelines

