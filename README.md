README.md (Task 2 – Titanic Dataset)
# Task 2: Cleaned & Visualized the Titanic Dataset

## 📌 Objective
The goal of this task was to **clean the Titanic dataset and perform simple visualizations**.  
We handled missing values, encoded categorical variables, and plotted survival rates by gender and passenger class.

---

## 📂 Dataset
- **Dataset**: Titanic – Machine Learning from Disaster  
- **Source**: [Kaggle – Titanic Dataset](https://www.kaggle.com/c/titanic/data)  
- **Files used**: `train.csv`  
- **Target Column**: `Survived` (0 = Did not survive, 1 = Survived)  
- **Rows**: 891  
- **Columns**: 12  

---

## 🔎 Steps Performed
1. **Loaded dataset with Pandas**
   ```python
   import pandas as pd
   df = pd.read_csv("train.csv")


Handled Missing Data

Filled missing Age values with median

Filled missing Embarked values with mode

Dropped the Cabin column (too many missing values)

Encoded Categorical Variables

Converted Sex into binary (male=0, female=1)

One-hot encoded Embarked (C, Q, S)

Visualizations

Survival by Gender

Survival by Passenger Class

📊 Findings

Females had a much higher survival rate than males.

Passengers in 1st class had higher chances of survival compared to 2nd and 3rd class.

The dataset had missing values in Age, Embarked, and mostly missing in Cabin.

📈 Example Visualizations

Survival Rate by Gender


Survival Rate by Passenger Class


✅ Outcome

Cleaned the Titanic dataset (handled missing values & encoding).

Visualized important patterns in survival rates.

Dataset is now ready for modeling in the next task.
