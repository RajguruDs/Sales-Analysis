# 📊 Sales Analysis Project

This project focuses on analyzing apparel sales data from Australia for the 4th quarter of 2020. The goal is to uncover patterns, identify top-performing categories, detect outliers, and generate time-based summary reports.

---

## 📁 Dataset

- **File Used:** `AusApparalSales4thQrt2020.csv`
- **Columns:**
  - `Date`: Date of the transaction
  - `Time`: Time of the transaction
  - `State`: State where the sale occurred
  - `Group`: Product category (e.g., Men, Women, Kids)
  - `Unit`: Number of units sold
  - `Sales`: Revenue from the sale

---

## ✅ Objectives

- Inspect and understand the dataset
- Clean and preprocess the data
- Perform descriptive statistical analysis
- Detect and handle outliers
- Identify best- and worst-performing product groups
- Generate weekly, monthly, and quarterly reports

---

## 🧰 Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (MinMaxScaler for normalization)

---

## 🔍 Key Insights

- **Data Skewness**: Sales and Units columns are **right-skewed** (positively distributed), meaning high-value sales were infrequent.
- **Top Product Group**: **Men's category** recorded the **highest total sales**.
- **Bottom Product Group**: **Kids' category** had the **lowest total sales**.
- **Outliers**: Detected and treated using the **IQR (Interquartile Range) method**.
- **Reports**: Weekly, monthly, and quarterly reports were generated to understand sales trends over time.

---

## 📊 Visualizations

- Histograms and KDE plots to show data distribution
- Boxplots for outlier detection
- Grouped bar charts for total sales per category (optional addition)

---

## 📂 Output Files

- `Weekly_Report.csv`
- `Monthly_Report.csv`
- `Quarterly_Report.csv`
---

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Ensure the CSV dataset is placed in the same directory as the notebook.
3. Open and run the notebook in **Jupyter** or **Google Colab**.

---



