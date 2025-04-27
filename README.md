# Super Shop Analysis

## 📊 Overview
This project analyzes sales data from a fictional "Super Shop" using Python, Pandas, Matplotlib, and Seaborn. The goal is to uncover insights about product performance, customer behavior, and business profitability.

## 📂 Dataset
The dataset (`super_shop_dataset.csv`) contains 5,000 records with 30 columns, including:
- **Product Details**: ID, category, sub-category, brand, price, discount
- **Inventory**: Stock levels, sold quantity, stock value
- **Financials**: Final price, purchase cost, profit
- **Customer Data**: Age, gender, customer type
- **Transactions**: Payment method, order status, delivery time

## 🛠️ Tools Used
- **Python 3** (with Jupyter Notebook)
- **Pandas** (for data manipulation)
- **Matplotlib & Seaborn** (for visualization)
- **Datetime** (for date parsing)

## 🔍 Key Findings

### 💰 Financial Performance
| Metric               | Value       |
|----------------------|-------------|
| Total Profit         | -600.19K    |
| Total Revenue        | 471.32M     |
| Profit Margin        | -0.13%      |
| Stock Value          | 947.92M     |

### 📦 Inventory Insights
- **Stock Turnover Ratio**: 0.49 (indicates slow-moving inventory)
- **Highest Stock Value Categories**:
  1. Clothing (196.29M)
  2. Groceries (192.25M)
  3. Electronics (192.18M)

### 🚚 Operations
- **Average Delivery Time**: 7.57 days
- **Return Rate**: 0.51%
- **Completed Orders**: 1,674

## 📈 Key Visualizations
- **Category Vs Stock_Value**: A bar chart showing Stock_Value for each category. 
- **Brand Vs Sold_Quantity**: A column chart showing Sold_Quantity for each Brand
- **Corr. Between Discount and Sold_Quantity among different Brands**: A scatter plot showing the corr. among different matrices 
