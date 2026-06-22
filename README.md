# DecodeLabs Internship
# 📊 Data Analytics Project 2 – Sales Analysis 

##  Project Overview

This project focuses on **data analysis and preprocessing** using Python.
The dataset contains sales-related information, and the goal is to clean, analyze, and extract meaningful insights from it.

---

##  Objectives

* Load and explore the dataset
* Handle missing values and duplicates
* Convert data types (e.g., Date column)
* Perform statistical analysis
* Analyze sales trends over time
* Visualize insights using graphs

---

##  Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📂 Dataset

The dataset is loaded from an Excel file:

```
Dataset for Data Analytics p2.xlsx
```

It contains information such as:

* Date
* Category (or similar fields)
* Total Price
* Other transaction-related columns

---

##  Data Preprocessing Steps

* Checked dataset shape and structure
* Converted `Date` column to datetime format
* Removed duplicate records
* Checked and handled missing values
* Cleaned column names

---

## 📈 Data Analysis

* Generated summary statistics using `.describe()`
* Calculated:

  * Mean of TotalPrice
  * Median of TotalPrice
  * Count of TotalPrice

---

##  Visualization

### Monthly Sales Trend

* Extracted month from Date column
* Grouped data by month
* Plotted sales trend using line graph

This helps in identifying:

* Sales growth 📈
* Seasonal patterns 📅

---

##  How to Run the Project

1. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl
   ```

2. Open the notebook:

   ```bash
   jupyter notebook DA_analysis_P2.ipynb
   ```

3. Run all cells step by step

---

##  Key Insights

* Sales trends over time can be clearly visualized
* Data cleaning improves analysis accuracy
* Monthly aggregation helps in business decision-making

---

##  Future Improvements

* Add more visualizations (bar charts, heatmaps)
* Perform category-wise analysis
* Build predictive models (sales forecasting)
* Create dashboard using Power BI / Tableau

---

##  Author

Dhanya Mary

---

##  Acknowledgment

This project is part of a **Data Analytics learning exercise** to understand real-world data preprocessing and visualization.
