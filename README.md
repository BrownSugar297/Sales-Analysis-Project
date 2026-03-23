# 🛍️ Diwali Sales Analysis

A Python-based exploratory data analysis (EDA) project that uncovers consumer purchasing patterns from Diwali season sales data — including insights across gender, age, geography, occupation, and product categories.

---

## 📌 Project Overview

This project analyzes a real-world retail dataset to identify key customer segments and their buying behavior during the Diwali festival season. The goal is to help businesses better understand their target audience and optimize sales strategies.

---

## 📁 Project Structure

```
Sales-Analysis-Project/
│
├── Sales Analysis.ipynb    # Main Jupyter Notebook with full EDA
├── Sales Data.csv          # Raw sales dataset
└── README.md               # Project documentation
```

---

## 🧰 Technologies Used

- **Python 3**
- **Pandas** — data manipulation & cleaning
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical plotting

---

## 📊 Dataset

The dataset contains customer transaction records with the following features:

| Column | Description |
|---|---|
| `User_ID` | Unique customer identifier |
| `Cust_name` | Customer name |
| `Product_ID` | Product identifier |
| `Gender` | Customer gender |
| `Age Group` | Age bracket of the customer |
| `Age` | Customer age |
| `Marital_Status` | Marital status (0 = Unmarried, 1 = Married) |
| `State` | Indian state of the customer |
| `Zone` | Geographic zone |
| `Occupation` | Customer's occupation |
| `Product_Category` | Category of purchased product |
| `Orders` | Number of orders placed |
| `Amount` | Total purchase amount (₹) |

---

## 🔍 Exploratory Data Analysis

The notebook walks through the following analysis dimensions:

### 👩 Gender
- Most buyers are **female**
- Female customers also have **higher purchasing power** than male customers

### 🎂 Age Group
- The dominant buyer segment is **females aged 26–35 years**

### 🗺️ State
- Top states by orders and revenue: **Uttar Pradesh, Maharashtra, and Karnataka**

### 💍 Marital Status
- Most buyers are **married women**, who also show higher spending

### 💼 Occupation
- Leading occupations among buyers: **IT, Healthcare, and Aviation**

### 🛒 Product Category
- Top-selling categories: **Food, Clothing, and Electronics**

---

## ✅ Conclusion

> **Married women aged 26–35 from Uttar Pradesh, Maharashtra, and Karnataka working in IT, Healthcare, or Aviation are the most likely to purchase products in the Food, Clothing, and Electronics categories.**

This insight can directly inform targeted marketing campaigns and inventory decisions for the Diwali season.

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install numpy pandas matplotlib seaborn
```

### Run the Notebook

```bash
git clone https://github.com/your-username/Sales-Analysis-Project.git
cd Sales-Analysis-Project
jupyter notebook "Sales Analysis.ipynb"
```

---

## 📬 Contact

Feel free to open an issue or reach out if you have any questions or suggestions!
