# 📊 SF Salaries Data Analysis Dashboard (Python)

## 📌 Project Overview

This project is a **complete Exploratory Data Analysis (EDA) and Visualization Dashboard** built using **Python, Pandas, Matplotlib, and Seaborn**.
The dataset contains salary information of public employees, including **job titles, base pay, overtime, benefits, and total compensation** across multiple years.

The goal of this project is to:

* Clean real-world messy data
* Perform meaningful analysis
* Visualize key insights in a **single dashboard using subplots**

This project is **beginner-to-intermediate friendly** and highly suitable for **Data Analyst / Business Analyst portfolios**.

---

## 📂 Dataset Information

* **Rows:** 143,713
* **Columns:** 13
* **Key Columns:**

  * `EmployeeName`
  * `JobTitle`
  * `BasePay`
  * `OvertimePay`
  * `OtherPay`
  * `Benefits`
  * `TotalPay`
  * `TotalPayBenefits`
  * `Year`

> ⚠️ The dataset contains missing values and non-numeric entries like **"Not Provided"**, making it ideal for practicing real-world data cleaning.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation & cleaning
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical plots

---

## 🔍 Data Cleaning Steps

* Checked null values across all columns
* Converted object columns to numeric using `pd.to_numeric()`
* Replaced `"Not Provided"` with `NaN`
* Dropped irrelevant columns (`Id`, `Notes`, `Agency`, `Status`)
* Handled missing values safely

---

## 📊 Analysis Performed

The project answers the following key analytical questions:

1. Display top and last rows of the dataset
2. Dataset shape and structure
3. Null reminder and data types
4. Most common employee job titles
5. Number of unique job titles
6. Job titles containing specific keywords (e.g., *Captain*)
7. Employees working in the Fire Department
8. Minimum, maximum, and average BasePay
9. Salary details of a specific employee
10. Highest-paid employee
11. Average BasePay by year
12. Average BasePay by job title
13. Top 5 most common jobs

---

## 📈 Dashboard Visualization

All major insights are visualized in **one single dashboard** using **matplotlib subplots**, including:

* Top 5 most common job titles
* Average BasePay trend over the years
* BasePay distribution
* Top 5 highest-paid employees
* Highest paying job titles
* Salary distribution for Captain roles

This makes analysis **clear, compact, and presentation-ready**.

---

## 👨‍💻 Author

**Divyanshu Joshi (DJ)**
Final Year B.Tech – Computer Science & Business Systems
Aspiring **Data Analyst / Business Analyst**

---

⭐ If you find this project useful, don’t forget to **star the repository**!
