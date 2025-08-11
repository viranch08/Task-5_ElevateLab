# Exploratory Data Analysis on Titanic Dataset

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset using Python in Google Colab.  
The goal is to explore the dataset, identify patterns, visualize trends, and summarize key findings about passenger survival.

---

## 📂 Dataset
**File:** `train.csv`  
**Source:** Titanic passenger data (Kaggle)  
**Shape:** 891 rows × 12 columns  

**Columns:**
- `PassengerId` – Unique passenger identifier
- `Survived` – Survival (0 = No, 1 = Yes)
- `Pclass` – Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Name` – Passenger name
- `Sex` – Gender
- `Age` – Age in years
- `SibSp` – # of siblings/spouses aboard
- `Parch` – # of parents/children aboard
- `Ticket` – Ticket number
- `Fare` – Passenger fare
- `Cabin` – Cabin number
- `Embarked` – Port of embarkation (C, Q, S)

---

## 🛠️ Tools & Libraries Used
- **Pandas** – Data loading and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical plots and styling
- **Scikit-learn** – Label encoding categorical variables

---

## 📊 Steps Performed

1. **Load the dataset**  
   ```python
   import pandas as pd
   df = pd.read_csv("train.csv")
