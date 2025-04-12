# Project---Black-Friday-Sales-Data-Analysis
This project explores the Black Friday Sales Data to uncover purchasing patterns and insights from various user demographics. The dataset includes multiple details about users, including their age, gender, occupation, and marital status, as well as information about the products they purchased during the Black Friday sale event. 

# 🛍️ Black Friday Sales Data Analysis

This project performs an exploratory data analysis (EDA) of the **Black Friday Sales dataset** using Python, Pandas, and visualization libraries like Matplotlib and Seaborn. The objective is to uncover insights from customer purchase behavior during Black Friday.

---

## 📚 Prerequisites

Before diving into the project, make sure you have the following knowledge and tools:

- **Basic Python** – Programming fundamentals.
- **Pandas** – For data manipulation and analysis.
- **Matplotlib & Seaborn** – For data visualization (e.g., bar plots, pie charts, box plots).
- **Jupyter Notebook** – For interactive code execution.
- **Basic Data Analysis** – Cleaning data, handling missing values, and performing EDA.

---

## 📦 Dataset Details

- **Name**: Black Friday Sales Data  
- **Size**: ~23 MB (CSV format)  
- **Rows**: 537,000+  
- **Columns**: 12  
- **Key Columns**:  
  `User_ID`, `Product_ID`, `Gender`, `Age`, `Occupation`, `City_Category`, `Stay_In_Current_City_Years`, `Marital_Status`, `Product_Category_1`, `Product_Category_2`, `Product_Category_3`, `Purchase`

- **Source**: [Download Dataset](#)

---

## 🧭 Project Structure & Steps

### 1. 📂 Walkthrough of the Dataset
- Load dataset into a Pandas DataFrame
- Examine structure and missing values
- Run `df.info()` for a quick overview  
🔗 [Code](#)

---

### 2. 📊 Analyzing Columns
- Focus on key columns like `Gender`, `Age`, `Marital_Status`, `Product_Category`, and `Purchase`
- Drop sparse columns (`Product_Category_2`, `Product_Category_3`)
- Use `unique()` and `nunique()` for data insight  
🔗 [Code](#)

---

### 3. 👩‍💼 Analyzing Gender
- Identify gender imbalance (more male customers)
- Use `groupby()` to see purchase trends by gender  
🔗 [Code](#)

---

### 4. 🎂 Analyzing Age & Marital Status
- Segment users by `Age` and `Marital_Status`
- Identify which groups spend more  
🔗 [Code](#)

---

### 5. 🔄 Multi-Column Analysis
- Combine `Age`, `Gender`, and `Marital_Status`
- Use visualizations (bar/pie charts) to identify combined patterns  
🔗 [Code](#)

---

### 6. 💼 Occupation & Products Analysis
- Examine how `Occupation` affects purchases
- Analyze top `Product_IDs` and `Product_Category_1` across occupations  
🔗 [Code](#)

---

### 7. ❤️ Combining Gender & Marital Status
- Combine `Gender` and `Marital_Status` to assess their influence
- Use Seaborn’s `countplot` for visualization  
🔗 [Code](#)

---

## 🧪 Tools Used

- Python 3.x  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook

---

## ✅ Outcomes

By the end of this analysis, you'll have a deeper understanding of:
- Customer demographics that spend more during Black Friday
- The influence of gender, age, marital status, and occupation
- Popular product categories and purchase behavior trends

---

## 📁 Repository Contents

- `notebooks/` – Jupyter Notebooks for each analysis step  
- `data/` – Dataset (or provide download link)  
- `README.md` – Project documentation (this file)

---

## 🧠 Final Thoughts

This project is great for practicing data wrangling, exploratory analysis, and visual storytelling. Ideal for aspiring data analysts and data scientists.
