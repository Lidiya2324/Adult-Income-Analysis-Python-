# Adult-Income-Analysis

## Project Overview
This project performs an in-depth exploratory data analysis (EDA) on the Adult Income dataset to identify the demographic and socioeconomic factors associated with earning more than $50K per year.

**The analysis focuses on:**

- Understanding income distribution
- Examining patterns across gender, education, occupation, age, and workclass
- Identifying which groups are more likely to be high earners
- Providing data-driven recommendations

## Tools Used
- Python (Pandas, NumPy, Matplotlib)
- Jupyter Notebook

## Dataset Description
The dataset contains 48,842 rows and 15 columns, including demographic variables (age, gender, race), work-related attributes (occupation, workclass, hours-per-week), and income category.

## Data Preparation
Main cleaning steps performed in the notebook:
- Converted income column to binary (0 = ≤50K, 1 = >50K)
- Replaced placeholder missing values (“?”)
- Standardized text fields (trimmed spaces)
- Created age groups for deeper analysis
  
Full code and detailed cleaning steps are included in the Jupyter notebook.

 ## 📊 Key KPIs

- 23.9% of individuals earn more than 50K
- High earners: average age 44.3, work 45.4 hours/week
- Gender gap: 30.4% men vs 10.9% women earn >50K
- Top education levels: Professional School, Doctorate, Masters
- Top occupations: Exec-managerial, Professional Specialty
- Peak earning age: 46–55 years

## 📈 Visualizations

### 1. Income Distribution


### 2. Income by Gender
![Income by Gender](images/income_by_gender.png)

### 3. Top 10 Education Levels by % Earning >50K
![Education Levels](images/education_levels.png)

### 4. Top 10 Occupations by % Earning >50K
![Occupation Income](images/occupation_income.png)

### 5. Income by Workclass
![Workclass Income](images/workclass_income.png)

### 6. Income Trend by Age Group
![Age Trend](images/age_trend.png)




