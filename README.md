# 🚲 Bike Sales Excel Dashboard

## 📌 Project Overview

This project focuses on building an interactive **Bike Sales Dashboard in Microsoft Excel**. It demonstrates the complete process of preparing sales data, creating pivot tables, generating visualizations, and designing an easy-to-use dashboard.

The dashboard allows users to explore bike purchasing patterns across different **demographic and customer-related factors**.

![Bike Sales Excel Dashboard]()

---

## 📊 Dataset

The project uses the **Bike Buyers 1000** dataset.

**Dataset Source:**  
https://www.kaggle.com/datasets/heeraldedhia/bike-buyers

The dataset contains customer information that can be analyzed to identify patterns related to bike purchases.

---

## 🛠️ Project Workflow

### 1. Data Cleaning

The raw dataset is prepared for analysis by:

- Identifying and removing duplicate records
- Standardizing categorical values
- Cleaning fields such as **Marital Status** and **Gender**
- Ensuring the data is consistent and suitable for analysis

### 2. Creating a Working Sheet

A separate working sheet is created by copying the original dataset.

This approach keeps the **raw data unchanged** while allowing the cleaned data to be modified and analyzed safely.

### 3. Building Pivot Tables

Pivot tables are created to summarize the cleaned dataset and identify useful trends.

These summaries are then used as the foundation for the dashboard visualizations.

### 4. Creating Visualizations

Different charts are used to present important bike sales insights, including:

- Average income by gender and bike purchase status
- Customer distribution based on commute distance
- Bike purchases across different age groups

### 5. Dashboard Development

The individual charts and visualizations are combined into a single **dashboard sheet**.

The dashboard is designed to provide a clear overview of bike sales while making the information easy to explore.

### 6. Chart Formatting

Charts are customized to improve readability and presentation by adjusting:

- Chart titles
- Axis labels
- Formatting
- Layout
- Overall visual appearance

---

## 📈 Dashboard Features

### 💰 Average Income by Gender & Bike Purchase

This visualization compares the **average income of customers** based on their gender and whether they purchased a bike.

### 🚗 Customer Commute Distance

This section shows how customers are distributed across different **commute-distance categories**, while also comparing bike purchase behavior.

### 👥 Customer Age Brackets

Customers are grouped into different age categories to analyze bike purchasing patterns among:

- **Adolescent**
- **Middle-Aged**
- **Old**

This helps identify which age groups are more likely to purchase a bike.

---

## 🔍 Key Analysis Areas

The dashboard can be used to explore relationships between:

- Gender and bike purchases
- Income and bike purchases
- Commute distance and purchasing behavior
- Age groups and bike purchases
- Customer demographics and overall bike sales

---

## 🚀 How to Use

1. Download the Bike Buyers dataset from the provided Kaggle source.
2. Open the Excel project.
3. Review the cleaned working data.
4. Explore the pivot tables used for analysis.
5. Navigate to the dashboard sheet.
6. Use the available interactive features to explore bike sales insights.

---

## 📁 Project Structure

```text
Bike-Sales-Excel-Dashboard/
│
├── Raw Data
│   └── Original bike buyers dataset
│
├── Working Sheet
│   └── Cleaned and prepared data
│
├── Pivot Tables
│   └── Summarized data for analysis
│
└── Dashboard
    └── Interactive bike sales visualizations
