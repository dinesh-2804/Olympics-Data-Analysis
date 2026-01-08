# 🏅 Olympics Data Analysis – Exploratory Data Analysis (EDA)

---

## 📌 Project Overview

This project performs a **comprehensive Exploratory Data Analysis (EDA)** on a large-scale **Olympics dataset** containing historical athlete participation and performance records.  
The objective is to **clean, analyze, and visualize** Olympic data to extract meaningful insights related to **demographics, physical attributes, medal distribution, countries, sports, and trends over time**.

This project is designed as a **portfolio-quality data analytics project**, suitable for recruiters and real-world data workflows.

---

## 📊 Dataset Description

- **Dataset Name:** Olympics Dataset  
- **Total Records:** ~70,000 athletes  
- **Total Features:** 15 columns  

### Key Attributes:
- Athlete Details: `Name`, `Sex`, `Age`
- Physical Attributes: `Height`, `Weight`
- Event Information: `Sport`, `Event`, `Season`, `Year`
- Country Representation: `Team`, `NOC`
- Performance Outcome: `Medal`

📁 Dataset file:
- `dataset_olympics.csv`

---

## 🔄 Project Workflow

### 1️⃣ Data Loading & Initial Inspection
- Loaded dataset using Pandas
- Explored structure using `head()`, `shape`, `info()`, and `describe()`

### 2️⃣ Data Cleaning & Preprocessing
- Handled **100% missing values** using statistical techniques:
  - Median imputation for skewed features (`Age`, `Weight`)
  - Mean imputation for normally distributed feature (`Height`)
- Removed duplicate and empty rows
- Standardized categorical values (case normalization, trimming)
- Converted data types (`Year → datetime`, categorical casting)
- Rounded numerical features for clarity

### 3️⃣ Exploratory Data Analysis (EDA)

#### 🔹 Univariate Analysis
- Distribution analysis of `Age`, `Height`, and `Weight`
- Gender, Medal, and Season frequency analysis
- Outlier detection using boxplots

#### 🔹 Bivariate Analysis
- **Numerical vs Numerical:** Height vs Weight
- **Categorical vs Categorical:** Gender vs Medal, Season vs Medal
- **Numerical vs Categorical:** Weight vs Medal
- Country-wise and event-wise medal comparisons

#### 🔹 Multivariate Analysis
- Age–Height–Weight relationships
- Gender–Sport–Medal interactions
- Country–Year medal trends
- Correlation heatmaps for numerical features

---

## 🔍 Key Insights

- Most Olympic athletes fall within the **20–30 age range**
- **Male participation** is historically higher, though **female representation has steadily increased**
- A small number of countries dominate **overall medal counts**
- **Height and Weight show strong positive correlation**
- Medal outcomes depend on **multiple interacting factors** such as age, sport type, and gender
- Total medals have **increased over time**, reflecting Olympic expansion

---

## 🛠 Tools & Technologies

- **Programming Language:** Python  
- **Libraries Used:**  
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  
- **Environment:** Jupyter Notebook  

---

## 📈 Results & Conclusion

This project demonstrates how structured EDA significantly improves data understanding and readiness for machine learning.  
The cleaned dataset and insights provide a strong foundation for **predictive modeling**, **feature engineering**, and **advanced analytics**.

---

## 🚀 Future Scope

- Build **machine learning models** to predict medal outcomes  
- Engineer advanced features such as **BMI, age groups, and experience levels**
- Create an **interactive dashboard** using Power BI, Tableau, or Streamlit
- Normalize medal counts using population or athlete participation metrics

---

## 📂 Project Files

- `Olympics_Data_Analysis.ipynb` – Complete EDA notebook  
- `dataset_olympics.csv` – Raw dataset  
- `README.md` – Project documentation  

---

## 👤 Author

**Dinesh Simakurthi**  
Data Analyst | Python | SQL | Data Visualization  

🔗 GitHub:   https://github.com/dinesh-2804
🔗 LinkedIn: https://www.linkedin.com/in/dinesh-hemanth-simakurthi/
---

⭐ If you find this project useful, feel free to **star the repository**!
