# 🛳 Titanic Dataset EDA – Elevate Labs

This project presents an exploratory data analysis (EDA) of the Titanic dataset to uncover patterns that influenced passenger survival. It includes data cleaning, statistical summary, and multiple visualizations to extract insights from the data.

---

## 📁 Dataset

- **Source**: `train.csv`
- **Description**: Contains information on passengers aboard the Titanic, including demographic data, ticket information, and survival outcome (`Survived` column: 0 = No, 1 = Yes).

---

## 📊 Analysis Overview

### 1. Data Exploration
- Loaded and examined structure with `.info()`, `.describe()`, and `.isnull().sum()`.
- Identified missing values in columns like `Age`, `Cabin`, and `Embarked`.

### 2. Data Preprocessing
- Addressed missing values (e.g., dropped or filled).
- Categorical data was prepared for analysis (some encoding steps were present).

### 3. Visual Insights

| Plot Title                              | Insight |
|----------------------------------------|---------|
| **Survival Distribution**              | More passengers died than survived. |
| **Age Distribution**                   | Most passengers were between 20–40 years old. |
| **Survival by Gender**                 | Females had a significantly higher survival rate. |
| **Survival by Passenger Class**        | 1st class had the highest survival rate. |
| **Correlation Heatmap**                | Fare and Pclass correlated with survival. |
| **Age by Survival (Boxplot)**          | Survivors tended to be younger. |
| **Survival by Embarked Port**          | Port `C` passengers had the highest survival rate. |
| **Fare vs. Age (Scatterplot)**         | Survivors often paid higher fares. |
| **Survival by Age Group**              | Children had the best survival rate. |
| **Survival by Class & Port (Heatmap)** | 1st class from port `C` had the highest survival. |
| **Survival by Siblings/Spouses**       | Solo travelers or those with one companion fared better. |

> **Note:** Plot numbers skipped Plot 7 and 11 due to it being info & a table.
---

## 🧠 Next Steps

- Implement machine learning models (e.g., Logistic Regression, Random Forest).
- Perform feature engineering: extract titles, group family members, or build age bands.
- Use cross-validation and hyperparameter tuning for better performance.
- Deploy a predictive survival classifier.

---

## 📦 Requirements

- Python
- pandas, matplotlib, seaborn
- Jupyter Notebook

---

## 📂 Files

- `Titanic EDA Python File.ipynb` – Main notebook containing all the EDA steps
- `Titanic Dataset.csv` – Titanic training dataset

---

## 📬 Contact

For any questions or suggestions, feel free to reach out!

