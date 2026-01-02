# HR Analytics — Statistics & Probability Analysis

## 1. What This Project Is About

This project uses statistics and probability to analyze an HR analytics dataset.

The goal is **not** to build models or predictions, but to demonstrate that I understand:

- How to classify variables correctly  
- How to choose appropriate statistical methods  
- How to check assumptions before applying tests  
- How to interpret results carefully and honestly  

This is a **statistics-first project**, not a machine learning project.

---

## 2. Why I Built This Project

I am transitioning into Data Science from a finance background, where understanding
assumptions, distributions, and interpretation is critical.

This project is designed to demonstrate **statistical thinking and rigor**, rather than
model-building or prediction accuracy.

---

## 3. About the Dataset

The dataset contains employee-level HR data commonly used for attrition and workforce
analysis.

This point is important because it limits what kinds of statistical claims are valid.
The data is **observational**, not experimental.

---

## 4. Variable Classification

All variables were classified **before** any analysis was performed, since correct
statistical analysis depends on understanding what type of data each variable represents.

### 4.1 Variables Excluded From Analysis

The following variables are excluded because they are identifiers or constants and do not
provide analytical value:

- EmpID  
- EmployeeNumber  
- EmployeeCount  
- Over18  
- StandardHours  

---

### 4.2 Binary Categorical Variables

These variables have two categories:

- Attrition  
- Gender  
- OverTime  

---

### 4.3 Nominal Categorical Variables

These variables represent categories with no natural order:

- Department  
- JobRole  
- BusinessTravel  
- EducationField  
- MaritalStatus  

---

### 4.4 Ordinal Categorical Variables

These variables have a natural order, but the distance between values is not guaranteed
to be equal:

- Education  
- EnvironmentSatisfaction  
- JobInvolvement  
- JobLevel  
- JobSatisfaction  
- PerformanceRating  
- RelationshipSatisfaction  
- StockOptionLevel  
- WorkLifeBalance  
- TrainingTimesLastYear  
- PercentSalaryHike  
- AgeGroup  
- SalarySlab  

---

### 4.5 Continuous Numerical Variables

These variables are numerical and measured on a continuous or ratio scale:

- Age  
- DailyRate  
- DistanceFromHome  
- HourlyRate  
- MonthlyIncome  
- MonthlyRate  
- NumCompaniesWorked  
- TotalWorkingYears  
- YearsAtCompany  
- YearsInCurrentRole  
- YearsSinceLastPromotion  
- YearsWithCurrManager  

---

## 5. Statistical Focus

This project focuses on:

- Descriptive statistics (means, medians, variability)  
- Probability distributions  
- Inferential statistics such as hypothesis testing  

Statistical tests are chosen based on:

- The type of variables involved  
- Distributional assumptions  
- Sample size  
- Independence of observations  

---

## 6. What This Project Does Not Attempt

To keep the analysis honest and focused, this project does **not** include:

- Machine learning or predictive models  
- Causal claims or cause-and-effect statements  
- A/B testing (the data is not experimental)  
- Dashboards or business recommendations  

---

## 7. Interpretation and Limitations

All results in this project represent **statistical associations**, not causal
relationships.

Conclusions are interpreted within the limits of observational data and the assumptions
required by each statistical method.

---

## 8. Repository Structure

