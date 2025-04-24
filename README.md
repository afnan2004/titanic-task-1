# 🧹 Titanic Dataset - Data Cleaning & Preprocessing

## 🎯 Objective
This repository contains my work for **Task 1** of the AI & ML Internship, focused on cleaning and preprocessing the Titanic dataset to make it ready for machine learning applications.

---

## 🛠️ Tools & Libraries Used
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Steps Completed

1. **Data Import & Exploration**
   - Loaded the Titanic dataset (`Titanic-Dataset.csv`)
   - Checked data types and identified missing values

2. **Handling Missing Values**
   - Filled missing `Age` values with the **median**
   - Filled missing `Embarked` values with the **mode**
   - Dropped the `Cabin` column due to high number of nulls
   - Dropped `PassengerId`, `Name`, and `Ticket` as they were not relevant to modeling

3. **Encoding Categorical Variables**
   - Applied **Label Encoding** to `Sex` and `Embarked` columns

4. **Feature Scaling**
   - Standardized `Age` and `Fare` using **StandardScaler**

5. **Outlier Detection & Removal**
   - Visualized outliers using **boxplots**
   - Removed outliers using the **IQR (Interquartile Range)** method


## 📁 Files Included

| File Name                   | Description                             |
|-----------------------------|-----------------------------------------|
| `Titanic-Dataset.csv`       | Original dataset                        |
| `cleaned_titanic.csv`       | Cleaned and preprocessed dataset        |
| `titanic_preprocessing.ipynb` | Notebook with all processing steps    |

