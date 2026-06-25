# 👨‍💼 Employee Lifestyle and Salary Analysis

## 📌 Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of an Employee Dataset using Python. The primary objective is to examine the relationships between employee age, healthy eating habits, active lifestyle scores, blood groups, and salary levels.

Through statistical analysis and visualization techniques, this project uncovers patterns that help understand employee wellness and its potential association with salary distribution.

---

## 🎯 Objectives

- Analyze employee demographic information.
- Study the relationship between age and salary.
- Examine healthy eating habits among employees.
- Explore active lifestyle patterns.
- Investigate salary distribution across different employee groups.
- Generate meaningful business insights through data visualization.

---

## 📊 Dataset Information

The dataset contains employee records with the following attributes:

| Feature | Description |
|----------|------------|
| ID | Unique employee identifier |
| Groups | Employee blood group category |
| Age | Employee age |
| Healthy Eating | Healthy eating score |
| Active Lifestyle | Active lifestyle score |
| Salary | Employee salary |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Analysis Performed

### Data Exploration
- Dataset loading and inspection
- Shape analysis
- Data type verification
- Column examination
- Data information summary

### Statistical Analysis
- Summary statistics
- Distribution analysis
- Feature exploration

### Visualization Analysis

#### Age vs Salary Analysis
- Scatter plot visualization
- Relationship identification between age and salary

#### Healthy Eating vs Active Lifestyle
- Correlation exploration
- Employee wellness analysis

#### Healthy Eating vs Salary
- Lifestyle impact analysis on salary trends

#### Group Distribution Analysis
- Countplot of employee groups
- Category frequency comparison

---

## 📈 Key Insights

### Employee Age Analysis
- Employees belong to various age groups.
- Salary varies significantly across age ranges.

### Healthy Eating Patterns
- Most employees maintain moderate healthy eating scores.
- Higher healthy eating scores indicate stronger wellness habits.

### Active Lifestyle Analysis
- Active lifestyle scores vary among employees.
- Lifestyle patterns can be compared with salary trends.

### Salary Distribution
- Employee salaries show considerable variation.
- Certain employees earn significantly higher salaries than others.

---

## 🧹 Data Filtering Operations

The project includes advanced filtering techniques such as:

### Employees with Healthy Eating Score Greater Than 8

```python
df[df['healthy_eating'] > 8]
```

### Employees with Salary Less Than 1000

```python
df[df['salary'] < 1000]
```

### Employees with Healthy Eating > 8 and Salary < 1000

```python
df[(df['healthy_eating'] > 8) & (df['salary'] < 1000)]
```

---

## 📊 Visualizations Included

✔ Scatter Plot: Age vs Salary

✔ Scatter Plot: Healthy Eating vs Active Lifestyle

✔ Scatter Plot: Healthy Eating vs Salary

✔ Count Plot of Employee Groups

✔ Statistical Summaries

✔ Employee Filtering Analysis

---

## 🚀 Project Workflow

```text
Data Collection
       ↓
Data Loading
       ↓
Data Exploration
       ↓
Statistical Analysis
       ↓
Visualization
       ↓
Pattern Discovery
       ↓
Business Insights
```

---

## 📂 Project Structure

```text
Employee-Lifestyle-and-Salary-Analysis/
│
├── Employee Dataset.csv
├── Employee_Analysis.ipynb
├── README.md
├── requirements.txt
│
├── Visualizations/
│   ├── age_salary_scatterplot.png
│   ├── healthy_lifestyle_scatterplot.png
│   ├── healthy_salary_scatterplot.png
│   └── groups_countplot.png
│
└── Results/
```

---

## ▶️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/Employee-Lifestyle-and-Salary-Analysis.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### Run Project

```bash
jupyter notebook
```

Open:

```text
Employee_Analysis.ipynb
```

---

## 📚 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning & Inspection
- Data Visualization
- Statistical Analysis
- Employee Data Analytics
- Python Programming
- Business Insight Generation

---

## 🔮 Future Enhancements

- Correlation Heatmap
- Outlier Detection
- Salary Prediction Model
- Employee Segmentation
- Machine Learning Integration
- Interactive Power BI Dashboard

---

## 👨‍💻 Author

**Aryan Nigam**

Aspiring Data Analyst | Python Developer | Power BI Enthusiast

### Skills
- Python
- Pandas
- NumPy
- SQL
- Power BI
- Machine Learning
- Data Visualization

---

## ⭐ If you found this project useful, please consider giving it a star.