# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project focuses on analyzing the Titanic dataset from Kaggle to explore the factors affecting passenger survival. The analysis was performed as part of a data science learning journey.

## 📦 Dataset Description

- **Target Variable:** `Survived` (0 = No, 1 = Yes)
- **Features:** `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`, etc.
- The dataset was cleaned, encoded, and visualized using Python libraries.

---

## 🧹 Data Cleaning & Preprocessing

- Missing `Age` values filled with median
- Missing `Embarked` values filled with mode
- `Cabin`, `Ticket`, and `Name` columns dropped
- `Sex` encoded (male=0, female=1)
- One-hot encoded `Embarked`
- Created new feature: **FamilySize = SibSp + Parch**

---

## 📊 Visualizations

### 1. Survival Count  
### 2. Survival Rate by Gender  
### 3. Age Distribution by Survival  
### 4. Survival Rate by Passenger Class  
### 5. Survival by Siblings/Spouses  
### 6. Survival by Parents/Children  
### 7. Fare Distribution  
### 8. Correlation Heatmap  

---

## 🔍 Insights

- **Females** had a significantly higher survival rate.
- **1st Class** passengers were more likely to survive than 2nd or 3rd.
- **Younger passengers** (especially under 10) had better chances.
- **Smaller families** (size 2–3) were more likely to survive.
- **Fare and Embarkation point** also influenced survival.

---

## 🛠 Tools Used

- `Python 3.9`
- `Pandas`
- `Matplotlib`
- `Seaborn`
- `Jupyter Notebook`

---

## 📎 Dataset Link

- [🔗 Titanic Dataset - Kaggle](https://www.kaggle.com/competitions/titanic/data)

---

## 🚀 How to Run

```bash
pip install pandas seaborn matplotlib
jupyter notebook Prodigy_DS_02.ipyn
