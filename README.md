# Bike Purchase Analysis Dashboard

## 📊 Project Overview
This project analyzes a dataset of potential customers to identify key factors influencing bike purchasing decisions. The outcome is an interactive Excel dashboard that provides actionable insights into customer demographics and behavior.

**Objective:** To uncover patterns and relationships between customer attributes (income, age, commute distance, etc.) and their likelihood of purchasing a bike. This analysis can be used to inform targeted marketing strategies.

---

## 🛠️ Process & Methodology

The analysis was conducted in four main stages:

1.  **Raw Data:** The initial, unprocessed dataset.
2.  **Data Cleaning & Transformation (Working Data):** Prepared the data for analysis.
3.  **Pivot Tables & Analysis:** Summarized and explored the data to find trends.
4.  **Dashboard & Visualization:** Created an interactive dashboard to present the findings.

### **Data Cleaning & Transformation Steps**
To ensure data quality and usability, the following steps were performed on the raw data:

*   **Removed Duplicates:** Eliminated duplicate rows to ensure the accuracy of the analysis using Excel's `Remove Duplicates` feature.
*   **Standardized Data:**
    *   **Marital Status:** Replaced "M" and "S" with "Married" and "Single" using the Find and Replace tool.
    *   **Gender:** Replaced "M" and "F" with "Male" and "Female".
    *   **Income:** Changed the data type of the Income column to Currency for correct formatting.
*   **Feature Engineering:**
    *   **Age Bands:** Created a new `Age Range` column to categorize continuous age data into meaningful groups for better analysis:
        *   **Adolescent:** \<30 years old
        *   **Middle Age:** 31-54 years old
        *   **Old:** \>55 years old
        *   *(This was achieved using a nested `IF` formula)*

---

## 📈 Key Questions & Insights

The dashboard was designed to answer the following key business questions:

### **1. What is the Average Income of Buyers vs. Non-Buyers?**
*   **Insight:** Customers who purchased a bike have a **higher average income** than those who did not. This suggests that income is a significant factor in purchasing power and should be considered in targeting.

### **2. How does Commute Distance influence Purchase Decisions?**
*   **Insight:** Customers with **shorter commute distances (0-5 miles)** are more likely to purchase a bike. This indicates that bikes are seen as a practical solution for short-distance travel, and marketing should be focused on urban or suburban areas where commutes are shorter.

### **3. Which Age Group Purchases the Most Bikes?**
*   **Insight:** The **"Middle Age"** is the primary buyer of bikes. 

### **4. Other Notable Insights:**
*   **Gender:** The data suggests a slight variation in average income and purchasing patterns between genders, with males having a higher average income in this dataset.
*   **Education:** The dashboard allows filtering by education level, which can help identify if specific educational backgrounds correlate with a higher likelihood of purchase.
*   **Region:** Purchase behavior can be compared across different geographic regions (Europe, North America, Pacific) to tailor regional marketing campaigns.

---



## 📁 Project Files

This repository contains the following key file:

*   `Bike Purchase Dataset.xlsx` - The main Excel workbook containing:
    *   `bike_buyers` - The original dataset (Raw data).
    *   `Working Sheet` - The cleaned and transformed data.
    *   `Pivot Table` - The tables used for analysis.
    *   `Dashboard` - The final, interactive dashboard with slicers.

---

## 🚀 How to Use the Dashboard

1.  Download the `Bike Purchase Dataset.xlsx` file.
2.  Open it in **Microsoft Excel**.
3.  Navigate to the **"Dashboard"** sheet.
4.  Use the **slicers** (e.g., Marital Status, Region, Education) to filter the data and explore different segments of the customer base interactively.

   
