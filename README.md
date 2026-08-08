# 🏦 Bank Customer Churn Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-Analysis-orange?logo=mysql)
![Excel](https://img.shields.io/badge/Excel-Dashboard-green?logo=microsoftexcel)
![Tableau](https://img.shields.io/badge/Tableau-Visualization-E97627?logo=tableau)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![License](https://img.shields.io/badge/License-MIT-yellow)

A complete **Data Analytics** project that explores customer churn in a banking institution using **SQL, Python, Excel, and Tableau**. The project analyzes customer behavior, identifies churn patterns, and provides business insights through interactive dashboards and visualizations.

---

# 📚 Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Dataset Information](#-dataset-information)
- [Repository Structure](#-repository-structure)
- [Project Files](#-project-files)
- [Tools & Technologies](#-tools--technologies)
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Dashboard Preview](#-dashboard-preview)
- [Key Business Insights](#-key-business-insights)
- [Machine Learning](#-machine-learning)
- [How to Run the Project](#-how-to-run-the-project)
- [Future Improvements](#-future-improvements)
- [License](#-license)
- [Author](#-author)

---

# 📌 Project Overview

Customer churn is a significant challenge for banks, as retaining existing customers is more cost-effective than acquiring new ones. This project analyzes customer demographics, financial information, and account activity to identify factors associated with customer churn.

The project demonstrates an end-to-end analytics workflow, including:

- Data Cleaning
- SQL Analysis
- Exploratory Data Analysis (EDA)
- Excel Dashboard
- Tableau Dashboard
- Business Insights
- Machine Learning Preparation

---

# 💼 Business Problem

Banks need to understand why customers leave and which customer segments are at higher risk of churn. By identifying these patterns, banks can:

- Improve customer retention
- Increase customer lifetime value
- Reduce acquisition costs
- Design targeted retention campaigns
- Support data-driven business decisions

---

# 🎯 Project Objectives

- Analyze customer demographics and financial behavior.
- Identify factors contributing to customer churn.
- Perform exploratory data analysis.
- Create interactive dashboards in Excel and Tableau.
- Generate actionable business insights.
- Prepare the dataset for machine learning classification models.

---

# 📊 Dataset Information

| Attribute | Description |
|------------|-------------|
| Domain | Banking |
| Task | Customer Churn Analysis |
| Problem Type | Binary Classification |
| Dataset Size | 10,000 Customers |
| Missing Values | None |
| Target Variable | Exited |

### Target Variable

| Value | Description |
|-------|-------------|
| 0 | Customer Retained |
| 1 | Customer Churned |

### Dataset Features

- Customer ID
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card Status
- Active Member
- Estimated Salary
- Exited (Target)

---

# 📂 Repository Structure

```
Bank_Customer_Churn_Analysis
│
├── Dashboard
│   └──  Customer_Churn_Dashboard.twbx
|
├── Data
│   ├── Churn_Modelling.csv
│   └── Churn_Modelling_Cleaned.csv
|
├── Excel
│   └── Customer_Churn_Excel_Dashboard.xlsx
|
├── Images
│   ├── Customer_Churn_Analysis_using_python (1).png
│   ├── Customer_Churn_Analysis_using_python (2).png
│   ├── Customer_Churn_Analysis_using_python (3).png
|   ├── Customer_Churn_Analysis_using_python (4).png
│   ├── Customer_Churn_Analysis_using_python (5).png
|   ├── Customer_Churn_Excel_Dashboard (1).png
│   ├── Customer_Churn_Excel_Dashboard (2).png
│   ├── Customer_Churn_Excel_Dashboard (3).png 
│   └── Customer_Churn_Tableau_Dashboard.png
|
├── Python
│   └── churn-analysis.ipynb

├── SQL
│   └── sql-analysis.ipynb
│
├── LICENSE
├── README.md
└── .gitignore
```

---

# 📁 Project Files

## 📊 Analysis

- **Python EDA Notebook**  
  https://github.com/JEISAMATHEW/Bank_Customer_Churn_Analysis/blob/main/Python/churn-analysis.ipynb

- **SQL Analysis Notebook**  
  https://github.com/JEISAMATHEW/Bank_Customer_Churn_Analysis/blob/main/SQL/sql-analysis.ipynb

---

## 📂 Dataset

- **Original Dataset**  
  https://github.com/JEISAMATHEW/Bank_Customer_Churn_Analysis/blob/main/Data/Churn_Modelling.csv

- **Cleaned Dataset**  
  https://github.com/JEISAMATHEW/Bank_Customer_Churn_Analysis/blob/main/Data/Churn_Modelling_Cleaned.csv

---

## 📈 Dashboards

- **Tableau Dashboard (.twbx)**  
  https://github.com/JEISAMATHEW/Bank_Customer_Churn_Analysis/blob/main/Dashboard/Customer_Churn_Dashboard.twbx

- **Excel Dashboard (.xlsx)**  
  https://github.com/JEISAMATHEW/Bank_Customer_Churn_Analysis/blob/main/Excel/Customer_Churn_Excel_Dashboard.xlsx

---

# 🛠 Tools & Technologies

| Tool | Purpose |
|------|----------|
| SQL | Data Analysis |
| Python | Data Cleaning & EDA |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Excel | Dashboard Development |
| Tableau | Interactive Dashboard |
| Git & GitHub | Version Control |

---

# 📈 Exploratory Data Analysis (EDA)

The project includes analysis of:

- Customer Distribution by Country
- Customer Distribution by Gender
- Churn by Country
- Churn by Gender
- Churn by Active Member
- Churn by Credit Card
- Churn by Age Group
- Average Balance by Country
- Average Salary by Gender
- Correlation Analysis

---

# 📸 Dashboard Preview

## 📊 Excel Dashboard - Overview

![Excel Dashboard 1](https://raw.githubusercontent.com/JEISAMATHEW/Bank_Customer_Churn_Analysis/main/Images/Customer_Churn_Excel_Dashboard%20(1).png)

---

## 📊 Excel Dashboard - Customer Analysis

![Excel Dashboard 2](https://raw.githubusercontent.com/JEISAMATHEW/Bank_Customer_Churn_Analysis/main/Images/Customer_Churn_Excel_Dashboard%20(2).png)

---

## 📋 Pivot Tables

![Pivot Tables](https://raw.githubusercontent.com/JEISAMATHEW/Bank_Customer_Churn_Analysis/main/Images/Customer_Churn_Excel_Dashboard%20(3).png)

---

## 📈 Tableau Dashboard

![Tableau Dashboard](https://raw.githubusercontent.com/JEISAMATHEW/Bank_Customer_Churn_Analysis/main/Images/Customer_Churn_Tableau_Dashboard.png)

---

## 📈 Python Analysis - Distribution of Categorical Variables

![Python Analysis 1](https://github.com/JEISAMATHEW/Bank_Customer_Churn_Analysis/blob/main/Images/Customer_Churn_Analysis_using_python%20(1).png)

---

## 📈 Python Analysis - Boxplots of Numerical Variables

![Python Analysis 2](https://github.com/JEISAMATHEW/Bank_Customer_Churn_Analysis/blob/main/Images/Customer_Churn_Analysis_using_python%20(2).png)

---

## 📈 Python Analysis - Bivariate Analysis - Churn Rate by Categorical Variables

![Python Analysis 3](https://github.com/JEISAMATHEW/Bank_Customer_Churn_Analysis/blob/main/Images/Customer_Churn_Analysis_using_python%20(3).png)

---

## 📈 Python Analysis - Relationship Between Numerical Variables

![Python Analysis 4](https://github.com/JEISAMATHEW/Bank_Customer_Churn_Analysis/blob/main/Images/Customer_Churn_Analysis_using_python%20(4).png)

---

## 📈 Python Analysis - Correlation Matrix of Numerical Variables

![Python Analysis 5](https://github.com/JEISAMATHEW/Bank_Customer_Churn_Analysis/blob/main/Images/Customer_Churn_Analysis_using_python%20(5).png)

---

# 🔍 Key Business Insights

- France has the highest number of customers.
- Germany has the highest customer churn among the three countries.
- Female customers show a relatively higher churn rate.
- Inactive members are more likely to churn than active members.
- Customers aged 50–59 exhibit the highest churn proportion.
- Germany has the highest average account balance.
- Average salaries are nearly identical across genders.
- Customers with fewer banking products tend to have higher churn.

---

---
# 📊 Data Analysis Workflow

The project follows a structured data analytics workflow:

1. **Data Collection**
   - Imported the Bank Customer Churn dataset.

2. **Data Cleaning**
   - Removed unnecessary columns.
   - Checked for missing values and duplicates.
   - Prepared a cleaned dataset for analysis.

3. **SQL Analysis**
   - Analyzed customer demographics.
   - Calculated churn rates across different customer segments.
   - Generated business-focused insights using SQL queries.

4. **Exploratory Data Analysis (EDA)**
   - Examined customer distributions.
   - Analyzed churn by geography, gender, age group, and activity status.
   - Identified relationships between customer attributes.

5. **Dashboard Development**
   - Built an interactive Excel dashboard using Pivot Tables, Charts, and Slicers.
   - Developed a Tableau dashboard for dynamic business visualization.

6. **Business Insights**
   - Identified key drivers of customer churn.
   - Presented actionable recommendations to improve customer retention.
---

# 🤖 Future Machine Learning Enhancements

The cleaned dataset has been prepared for developing customer churn prediction models in future versions of this project. While the current project focuses on data cleaning, exploratory data analysis (EDA), SQL analysis, and dashboard development, the dataset is suitable for implementing machine learning models to predict customer churn.

## Potential Machine Learning Models

The following classification algorithms can be explored:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost
- LightGBM
- CatBoost

## Model Evaluation Metrics

The performance of the models can be evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

## Future Scope

Future enhancements of this project may include:

- Feature Engineering
- Feature Selection
- Hyperparameter Tuning
- Cross-Validation
- Model Comparison
- Feature Importance Analysis
- Model Deployment using Streamlit or Flask
---

# 🚀 How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/JEISAMATHEW/Bank_Customer_Churn_Analysis.git
```

### Navigate to the Project Folder

```bash
cd Bank_Customer_Churn_Analysis
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

- `Analysis/churn-analysis.ipynb`
- `Analysis/sql-analysis.ipynb`

---

# 📌 Future Improvements

- Develop predictive machine learning models.
- Perform hyperparameter tuning.
- Deploy the model using Streamlit or Flask.
- Add Power BI dashboards.
- Implement feature importance and model explainability.

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👩‍💻 Author

**Jeisa Mathew**

- GitHub: https://github.com/JEISAMATHEW
- LinkedIn: https://www.linkedin.com/in/jeisamathew

---

# 🙌 Acknowledgements

This project was developed as part of my Data Analytics and Machine Learning learning journey to strengthen practical skills in SQL, Python, Excel, Tableau, data visualization, and business analytics.

If you found this project useful or interesting, please consider giving it a ⭐ on GitHub!
