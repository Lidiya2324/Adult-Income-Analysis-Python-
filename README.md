# Adult-Income-Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Key KPIs](#key-kpis)
- [Recommendations](#recommendations)

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

 ## Key KPIs

- 23.9% of individuals earn more than 50K
- High earners: average age 44.3, work 45.4 hours/week
- Gender gap: 30.4% men vs 10.9% women earn >50K
- Top education levels: Professional School, Doctorate, Masters
- Top occupations: Exec-managerial, Professional Specialty
- Peak earning age: 46–55 years

## 📈 Visualizations

### 1. Income Distribution
<img width="519" height="340" alt="Income Distribution (Bar Chart" src="https://github.com/user-attachments/assets/a2ddf889-ae5c-4387-a4af-f8c72750d89c" />

### 2. Income by Gender
<img width="529" height="319" alt="Income by Gender (Bar Chart)" src="https://github.com/user-attachments/assets/fcba3641-b51a-4bee-9a8c-323dfc7d5e96" />

### 3. Top 10 Education Levels by % Earning >50K
<img width="843" height="323" alt="Income by Education Level (Top 10)" src="https://github.com/user-attachments/assets/7b367a31-2b5f-4953-b124-1e816203e9b7" />

### 4. Top 10 Occupations by % Earning >50K
<img width="916" height="311" alt="Top 10 Occupations by  Earning" src="https://github.com/user-attachments/assets/e7ff0e23-8885-4019-9c97-b48611416dd4" />

### 5. Income by Workclass
<img width="852" height="311" alt="Income by Workclass¶" src="https://github.com/user-attachments/assets/1113193d-9dad-477c-9e52-0c20b3dd3c7d" />

### 6. Income Trend by Age Group
<img width="916" height="311" alt="Top 10 Occupations by  Earning" src="https://github.com/user-attachments/assets/919d8780-de46-437c-8d02-d453e9ae7442" />

## 💡Insights

- Men are almost 3x more likely to earn >50K.
- Advanced degrees (Prof-school, Doctorate, Masters) dramatically increase chances of high income.
- Leadership, professional, and tech roles dominate high-earning categories.
- Income peaks around 46–55 years due to career experience.
- High earners work more hours consistently, showing a strong link between weekly hours and income.
- Self-employed individuals with incorporated businesses perform best.

## Recommendations

- Encourage advanced education and career development
- Implement programs to reduce gender income gap
- Promote upskilling into professional/managerial roles
- Support early-career individuals (<35) through training initiatives

