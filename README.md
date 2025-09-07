# 🚴‍♂️ Bike Buyers Data Analysis (Excel Project)

This project explores a dataset of **bike buyers** using Excel.  
The goal is to analyze customer demographics, lifestyle factors, and their likelihood of purchasing a bike.  

The project includes **data cleaning, transformation, pivot tables, and dashboards** to summarize insights in an interactive way.

---

## 📑 Table of Contents

1. [Project Overview](#-project-overview)  
2. [Dataset](#-dataset)  
3. [Data Cleaning](#-data-cleaning)  
4. [Analysis](#-analysis)  
5. [Pivot Tables](#-pivot-tables)  
6. [Dashboard](#-dashboard)  
7. [Insights](#-insights)  
8. [Tech Stack](#-tech-stack)  
9. [How to Use](#-how-to-use)  
10. [Future Improvements](#-future-improvements)  
11. [License](#-license)  

---

## 📖 Project Overview

The **Bike Buyers dataset** contains customer demographic and lifestyle data, with a target column `Purchased Bike`.  

The main objectives are to:  
- Understand customer segments most likely to purchase a bike.  
- Explore how **income, age, marital status, education, occupation, commute distance, and region** affect purchase behavior.  
- Build a professional **Excel dashboard** for interactive exploration.  

---

## 📂 Dataset

The dataset includes the following columns:

- `ID` – Unique identifier  
- `Marital Status` – Single or Married  
- `Gender` – Male/Female  
- `Income` – Annual income of the customer  
- `Children` – Number of children  
- `Education` – Highest education attained  
- `Occupation` – Type of work (Professional, Clerical, Skilled Manual, etc.)  
- `Home Owner` – Yes/No  
- `Cars` – Number of cars owned  
- `Commute Distance` – Distance to work (e.g., 0-1 Miles, 5-10 Miles)  
- `Region` – Geographic region (Europe, Pacific, North America)  
- `Age` – Age of the customer  
- `Purchased Bike` – Target variable (Yes/No)  

---

## 🧼 Data Cleaning

Performed in the **working sheet**:  
- Removed duplicate records.  
- Standardized categorical fields (e.g., “M/F” → “Male/Female”).  
- Formatted columns for **numeric values and dates**.  
- Created calculated columns for age grouping and commute categories.  

---

## 📊 Analysis

Some of the questions explored:  

- What is the **average income** of bike buyers vs non-buyers?  
- Does **marital status** affect bike purchase decisions?  
- Which **age groups** are more likely to purchase bikes?  
- How does **commute distance** correlate with bike purchases?  
- Do **region and occupation** influence purchase trends?  

---

## 📑 Pivot Tables

Pivot tables were created to:  
- Compare **purchasers vs non-purchasers** by income group.  
- Summarize purchases by **gender, marital status, and children**.  
- Analyze **region-wise sales distribution**.  
- Explore the effect of **education and occupation** on bike buying behavior.  

---

## 📊 Dashboard

An interactive Excel **dashboard** was built (in the “dashboard” sheet) including:  
- 🚹🚺 **Gender distribution of buyers**  
- 💰 **Income levels and bike purchases**  
- 📍 **Regional breakdown**  
- 🚗 **Commute distance vs purchase decision**  
- 📈 **Age group comparisons**  

The dashboard enables quick filtering and visualization of key insights.  

---

## 📈 Insights

- Higher-income individuals are **more likely** to purchase bikes.  
- Younger customers (30–45) show the **highest purchase rates**.  
- **Short commute distances** strongly correlate with bike purchases.  
- Married individuals and those with fewer children are **slightly more likely** to buy bikes.  
- Professionals tend to purchase more bikes compared to Clerical/Skilled Manual workers.  

---

## 🧑‍💻 Tech Stack

- **Microsoft Excel** → Data cleaning, analysis, pivot tables  
- **Excel Dashboards** → Interactive charts and slicers  

---

## 🌟 How to Use

1. Download the Excel file from this repository.  
2. Open it in **Microsoft Excel** (or Google Sheets with limited functionality).  
3. Explore:  
   - `bike_buyers` → Raw dataset  
   - `working sheet` → Cleaned and transformed data  
   - `pivot table` → Pivot tables for analysis  
   - `dashboard` → Interactive dashboard  

---

## 📌 Future Improvements

- Automate data cleaning with **Power Query**.  
- Add **predictive modeling** using Python or Power BI.  
- Extend analysis with **time-series data** if available.  

---

## 📜 License

This project is licensed under the **MIT License**.  
