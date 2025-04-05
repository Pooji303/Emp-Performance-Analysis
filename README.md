# **Employee Performance Analysis – INX Future Inc.**

## **Project Overview**
The **Employee Performance Analysis** project focuses on leveraging data analytics and machine learning to identify the key drivers of employee performance. The goal is to help **INX Future Inc.** enhance productivity, guide strategic hiring decisions, and design better training and retention programs.

---

## **Problem Statement**

### **Task 1: Department-wise Performance Analysis**
- Understand how employee performance varies across different departments.
- Identify high-performing vs. underperforming departments.

### **Task 2: Key Factor Identification**
- Discover the **top 3 features** that significantly impact employee performance.
- Use correlation analysis and feature selection techniques to isolate these drivers.

### **Task 3: Predictive Modeling**
- Build a supervised machine learning model to predict employee performance.
- Use models such as **Logistic Regression, Decision Trees**, and **Random Forest**.
- Tune and validate models using cross-validation and scaling techniques.

### **Task 4: Business Recommendations**
- Provide **data-backed suggestions** to improve performance and reduce attrition.
- Focus on personalized engagement strategies, department-specific interventions, and predictive hiring.

---

## **Dataset Information**

The dataset contains anonymized employee information across various departments and roles. Key features include:

| **Feature Name**           | **Description**                                |
|----------------------------|------------------------------------------------|
| `education`                | Education qualification                        |
| `joining_year`             | Year of joining                                |
| `gender`                   | Gender of the employee                         |
| `recruitment_channel`      | Source of recruitment                          |
| `no_of_trainings`          | Trainings attended in the past year            |
| `age`                      | Age of the employee                            |
| `previous_year_rating`     | Rating from the previous year                  |
| `length_of_service`        | Years of experience in the company             |
| `KPIs_met >80%`            | Whether the KPI target was achieved            |
| `awards_won?`              | Whether the employee won an award              |
| `avg_training_score`       | Average training score                         |
| `department`               | Department name                                |
| `employee_performance`     | Target variable (0: Low, 1: Medium, 2: High)   |

---

## **Repository Structure**

├── data/ │
├── raw/ # Original HR data │
└── processed/ # Cleaned and transformed data │
├── notebooks/ │
└── IABAC.PROJ.ipynb # Complete pipeline: EDA, modeling, insights │
├── src/ │
├── data_processing.py # Preprocessing and transformation scripts │ 
├── model_training.py # ML training and evaluation │ 
└── utils.py # Utility functions │ 
├── reports/ │
├── performance_report.pdf # Insights and strategic findings │ 
└── summary.md # Summary of analysis and recommendations

---

## **Technologies Used**

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Machine Learning Models:** Logistic Regression, Decision Tree, Random Forest  
- **Tools:** Jupyter Notebook, Git, Power BI (optional for dashboarding)

---

## **Key Insights**

- **Top Factors Affecting Performance:**
  - *Average Training Score*
  - *Previous Year Rating*
  - *KPI > 80% Completion Status*

- **Departmental Variance:** Some departments consistently show lower performance due to fewer training opportunities or lower KPI achievements.

- **Random Forest** provided the most balanced model in terms of prediction and interpretability.

---

## **Next Steps & Recommendations**

- Deploy the performance prediction model for HR screening and performance reviews.
- Recommend customized training programs based on performance predictors.
- Build dashboards in **Power BI** to track departmental and company-wide performance over time.

