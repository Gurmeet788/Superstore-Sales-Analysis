# 🛒 Superstore Sales Analysis 📊

This project performs a comprehensive analysis of sales data from a fictional superstore. It explores trends in revenue, top-performing products, regional sales distribution, and highlights outliers to gain actionable business insights.

## 📁 Dataset

- **Source**: [Kaggle Superstore Dataset](https://www.kaggle.com/datasets)
- **Records**: ~10,000 orders
- **Fields**: Order Date, Ship Date, Product Name, Region, Sales, Quantity, Discount, Profit, etc.

## 🧹 Data Cleaning

- Removed extra spaces in column names
- Checked for and handled missing values
- Converted `Order Date` and `Ship Date` to `datetime`
- Created new columns like:
  - `Shipping Days = Ship Date - Order Date`
  - `Unit Price = Sales / Quantity`

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Sales Insights
- **Total Sales by Product**: Top-selling products by revenue
- **Total Sales by Region**: Regional comparison via pie chart
- **Top 5 Products**: Based on revenue
- **Monthly Sales Trends**: Line graph showing monthly performance

### 🔹 Bonus Features
- **Moving Average**: 3-month moving average of sales to smooth trends
- **Best Selling Product per Month**
- **Box Plot**: Sales distribution across regions with outliers highlighted

## 📈 Visualizations

- Bar chart: Top 10 products by sales
- Pie chart: Sales by region
- Line chart: Monthly sales & moving average
- Box plot: Sales distribution by region

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

📌 Author
👨‍💻 Gurmeet —  [Kaggle]([https://www.kaggle.com/datasets](https://www.kaggle.com/gurmeet788))
