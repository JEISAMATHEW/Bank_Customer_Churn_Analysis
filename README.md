# 🏦 Bank Customer Churn Analysis
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-Analysis-orange?logo=mysql)
![Excel](https://img.shields.io/badge/Excel-Dashboard-green?logo=microsoftexcel)
![Tableau](https://img.shields.io/badge/Tableau-Visualization-E97627?logo=tableau)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![License](https://img.shields.io/badge/License-MIT-yellow)

A complete **Data Analytics** project that analyzes customer churn in a banking institution using **SQL, Python, Excel, and Tableau**.
The project explores customer demographics, financial characteristics, account activity, and behavioral patterns to identify factors associated with customer churn and generate actionable business insights.

---

# 📚 Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Dataset Information](#-dataset-information)
- [Repository Structure](#-repository-structure)
- [Project Files](#-project-files)
- [Tools & Technologies](#-tools--technologies)
- [Data Analysis Workflow](#-data-analysis-workflow)
- [Exploratory Data Analysis](#-exploratory-data-analysis-eda)
- [Dashboard Preview](#-dashboard-preview)
- [Key Business Insights](#-key-business-insights)
- [Future Machine Learning Enhancements](#-future-machine-learning-enhancements)
- [How to Run the Project](#-how-to-run-the-project)
- [Future Improvements](#-future-improvements)
- [License](#-license)
- [Author](#-author)
- [Acknowledgements](#-acknowledgements)

---

# 📌 Project Overview

Customer churn is a significant challenge for banking institutions because losing existing customers can negatively impact revenue, customer lifetime value, and long-term growth.

This project analyzes customer demographics, financial information, product usage, and account activity to identify patterns associated with customer churn.

The project demonstrates an end-to-end **Data Analytics workflow**, including:

- Data Cleaning
- SQL Analysis
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Excel Dashboard
- Tableau Dashboard
- Business Insights
- Machine Learning Preparation

---

# 💼 Business Problem

Banks need to understand:

- Why customers leave the bank
- Which customer segments have higher churn
- Whether demographic characteristics influence churn
- Whether customer activity and product usage affect churn
- Which customer groups should be targeted for retention campaigns

Understanding these patterns can help banks:

- Improve customer retention
- Increase customer lifetime value
- Reduce customer acquisition costs
- Develop targeted retention strategies
- Support data-driven decision-making

---

# 🎯 Project Objectives

The main objectives of this project are to:

- Analyze customer demographics and financial characteristics.
- Understand customer churn patterns.
- Identify customer segments with higher churn rates.
- Analyze the relationship between customer attributes and churn.
- Perform exploratory data analysis using Python.
- Perform business-focused analysis using SQL.
- Build interactive dashboards using Excel and Tableau.
- Generate actionable business insights.
- Prepare the dataset for future machine learning implementation.

---

# 📊 Dataset Information

| Attribute | Description |
|---|---|
| Domain | Banking |
| Task | Customer Churn Analysis |
| Problem Type | Binary Classification |
| Dataset Size | 10,000 Customers |
| Missing Values | None |
| Target Variable | `Exited` |

## Target Variable

| Value | Description |
|---:|---|
| 0 | Customer Retained |
| 1 | Customer Churned |

## Dataset Features

| Feature | Description |
|---|---|
| `RowNumber` | Dataset row identifier |
| `CustomerId` | Unique customer identifier |
| `Surname` | Customer surname |
| `CreditScore` | Customer credit score |
| `Geography` | Customer country |
| `Gender` | Customer gender |
| `Age` | Customer age |
| `Tenure` | Number of years with the bank |
| `Balance` | Customer account balance |
| `NumOfProducts` | Number of bank products used |
| `HasCrCard` | Credit card ownership status |
| `IsActiveMember` | Customer activity status |
| `EstimatedSalary` | Estimated customer salary |
| `Exited` | Churn indicator |

---

# 📂 Repository Structure

```text
Bank_Customer_Churn_Analysis
│
├── Dashboard
│   └── Customer_Churn_Dashboard.twbx
│
├── Data
│   ├── Churn_Modelling.csv
│   └── Churn_Modelling_Cleaned.csv
│
├── Excel
│   └── Customer_Churn_Excel_Dashboard.xlsx
│
├── Images
│   ├── Customer_Churn_Analysis_using_python (1).png
│   ├── Customer_Churn_Analysis_using_python (2).png
│   ├── Customer_Churn_Analysis_using_python (3).png
│   ├── Customer_Churn_Analysis_using_python (4).png
│   ├── Customer_Churn_Analysis_using_python (5).png
│   ├── Customer_Churn_Excel_Dashboard (1).png
│   ├── Customer_Churn_Excel_Dashboard (2).png
│   ├── Customer_Churn_Excel_Dashboard (3).png
│   └── Customer_Churn_Tableau_Dashboard.png
│
├── Python
│   └── churn-analysis.ipynb
│
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

# 📊 Data Analysis Workflow

The project follows a structured data analytics workflow:

1. **Data Collection**

   - Imported the Bank Customer Churn dataset.

2. **Data Cleaning**

   - Removed unnecessary columns.
   - Checked for missing values.
   - Checked for duplicate records.
   - Prepared a cleaned dataset for analysis.

3. **SQL Analysis**

   - Analyzed customer demographics.
   - Calculated churn rates across different customer segments.
   - Analyzed customer activity and product usage.
   - Generated business-focused insights using SQL queries.

4. **Exploratory Data Analysis (EDA)**

   - Examined categorical variable distributions.
   - Examined numerical variable distributions.
   - Performed univariate analysis.
   - Performed bivariate analysis.
   - Analyzed churn across customer segments.
   - Identified relationships between numerical variables.
   - Performed correlation analysis.

5. **Dashboard Development**

   - Built an interactive Excel dashboard using Pivot Tables, Charts, and Slicers.
   - Developed a Tableau dashboard for dynamic business visualization.

6. **Business Insights**

   - Identified key patterns associated with customer churn.
   - Identified higher-risk customer segments.
   - Presented actionable recommendations to improve customer retention.

---

# 📈 Exploratory Data Analysis (EDA)

The project includes comprehensive **Univariate and Bivariate Analysis**.

## 🔹 Univariate Analysis

### Vertical Bar Charts

The following categorical variables were analyzed using vertical bar charts:

- `Exited`
- `Geography`
- `Gender`
- `Tenure`
- `NumOfProducts`
- `HasCrCard`
- `IsActiveMember`

### Horizontal Bar Charts

Categorical distributions were also analyzed using horizontal bar charts to provide an alternative comparison of category frequencies.

### Histograms

Numerical variables were analyzed using histograms to understand their distributions:

- `CreditScore`
- `Age`
- `Tenure`
- `Balance`
- `NumOfProducts`
- `EstimatedSalary`

### Boxplots

Boxplots were used to examine the distribution, median, spread, and potential outliers of numerical variables.

---

## 🔹 Bivariate Analysis

Bivariate analysis was performed to identify relationships between customer attributes and churn.

### Vertical Column Bar Charts

Churn rates were analyzed across:

- Geography
- Gender
- Tenure
- Number of Products
- Credit Card Status
- Active Member Status

### Horizontal Bar Charts

Churn rates across categorical variables were also visualized using horizontal bar charts.

### Boxplots

The distribution of numerical variables was compared across churn status:

- Age vs Exited
- Balance vs Exited
- Credit Score vs Exited
- Estimated Salary vs Exited
- Tenure vs Exited

### Scatter Plots

Relationships between numerical variables were analyzed using scatter plots.

Examples include:

- Age vs Balance
- Credit Score vs Balance
- Age vs Estimated Salary

### Correlation Matrix

A correlation heatmap was created to analyze relationships among numerical variables and identify variables associated with customer churn.

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

Based on the analysis:

- France has the highest number of customers.
- Germany has the highest customer churn among the three countries.
- Female customers show a relatively higher churn rate.
- Inactive members are more likely to churn than active members.
- Customers aged 50–59 exhibit the highest churn proportion.
- Germany has the highest average account balance.
- Average salaries are nearly identical across genders.
- Customers with fewer banking products tend to have higher churn.
- Customer activity, age, geography, and product usage provide useful signals for customer retention analysis.

These findings can help banking institutions develop more targeted customer-retention strategies and improve customer engagement.

---

# 🤖 Future Machine Learning Enhancements

The cleaned dataset has been prepared for developing customer churn prediction models in future versions of this project.

While the current project focuses on **Data Analytics, SQL, Python EDA, Excel, and Tableau**, the dataset provides a strong foundation for implementing machine learning classification models.

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

The performance of future models can be evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

## Future Scope

Future machine learning enhancements may include:

- Feature Engineering
- Feature Selection
- Train-Test Split
- Cross-Validation
- Hyperparameter Tuning
- Model Comparison
- Feature Importance Analysis
- Model Explainability
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

- `Python/churn-analysis.ipynb`
- `SQL/sql-analysis.ipynb`

---

# 📌 Future Improvements

- Develop predictive machine learning models.
- Perform feature engineering and feature selection.
- Perform hyperparameter tuning.
- Implement cross-validation.
- Compare multiple machine learning models.
- Implement feature importance analysis.
- Add model explainability using SHAP.
- Deploy the churn prediction model using Streamlit.
- Add Power BI dashboards.
- Develop a real-time customer churn monitoring system.

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👩‍💻 Author

**Jeisa Mathew**

**Data Analytics | SQL | Python | Excel | Tableau | Machine Learning**

- GitHub: https://github.com/JEISAMATHEW
- LinkedIn: https://www.linkedin.com/in/jeisamathew

---

# 🙌 Acknowledgements

This project was developed as part of my **Data Analytics and Machine Learning learning journey** to strengthen practical skills in:

- SQL
- Python
- Pandas
- NumPy
- Data Visualization
- Excel
- Tableau
- Exploratory Data Analysis
- Business Intelligence
- Machine Learning

The project demonstrates an end-to-end approach to analyzing a real-world business problem using data.

If you found this project useful or interesting, please consider giving it a ⭐ on GitHub!
