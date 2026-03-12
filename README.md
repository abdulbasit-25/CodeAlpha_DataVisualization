# CodeAlpha Data Analytics Internship — Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project was completed as part of the **Data Analytics Internship Program by CodeAlpha**.  
The objective is to perform **Exploratory Data Analysis (EDA)** on an employee dataset to understand its structure, identify patterns, detect anomalies, and extract actionable insights.

EDA is an essential step before advanced analytics or machine learning as it helps to explore the data thoroughly.

---

## 🎯 Objectives
- Explore dataset structure and variables
- Perform statistical analysis
- Identify trends and patterns
- Detect missing values and anomalies
- Visualize relationships between variables
- Extract meaningful insights from the data

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

## 📂 Project Structure

CodeAlpha_EDA_Project/
│
├── eda_analysis.ipynb # Main analysis notebook
├── employee_dummy_dataset.csv # Dataset used for analysis
├── README.md # Project documentation
└── images/ # Folder containing all plots
├── Age Distribution OF Employees.png
├── Salary Distribution.png
├── Employees per Department.png
├── Gender Distribution.png
├── Performance Rating Distribution.png
├── Experience vs Salary.png
├── Salary by Department.png
├── Salary vs Performance.png
└── Correlation Analysis.png


---

## 📊 Dataset Description
| Column | Description |
|--------|-------------|
| EmployeeID | Unique ID for each employee |
| Age | Age of employee |
| Gender | Male/Female |
| Department | Department employee works in |
| YearsExperience | Total years of experience |
| Salary | Employee salary |
| Performance | Performance rating |

---

## 🔎 Exploratory Data Analysis Steps
1. **Data Loading:** Imported dataset using Pandas and checked its shape and structure.  
2. **Data Inspection:** Viewed sample records, column names, and data types.  
3. **Statistical Summary:** Generated summary statistics (mean, median, std, etc.).  
4. **Data Cleaning:** Checked for missing values and validated unique categorical values.  
5. **Data Visualization:** Created plots to visualize distributions, relationships, and correlations.

### Visualizations
- ![Age Distribution](images/Age Distribution OF Employees.png)
- ![Salary Distribution](images/Salary Distribution.png)
- ![Employees per Department](images/Employees per Department.png)
- ![Gender Distribution](images/Gender Distribution.png)
- ![Performance Rating Distribution](images/Performance Rating Distribution.png)
- ![Experience vs Salary](images/Experience vs Salary.png)
- ![Salary by Department](images/Salary by Department.png)
- ![Salary vs Performance](images/Salary vs Performance.png)
- ![Correlation Analysis](images/Correlation Analysis.png)

---

## 📈 Key Insights
- Salary generally **increases with years of experience**.
- Different departments show **variation in salary levels**.
- Most employees fall within the **mid-age range**.
- Employee **performance ratings influence salary distribution**.

---

## 🚀 How to Run the Project
1. Clone the repository:

```bash
git clone https://github.com/abdulbasit-25/CodeAlpha_EDA_Project.git

Install required libraries:

pip install pandas matplotlib seaborn numpy

Open and run the notebook in Jupyter Notebook or Google Colab.
