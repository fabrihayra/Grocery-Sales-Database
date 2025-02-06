# **Grocery Sales Data Analysis**

## **Project Overview**
This project focuses on analyzing a grocery sales dataset to gain insights into **supply chain efficiency, logistics, and sales performance**. The goal is to **identify key trends, optimize inventory management, and enhance business decision-making** based on data-driven insights.

---
## **Dataset Information**
The dataset includes the following files:
- **sales.csv** – Contains transaction-level sales data.
- **products.csv** – List of products with pricing and category details.
- **categories.csv** – Product categories.
- **customers.csv** – Customer demographics and locations.
- **employees.csv** – Sales representatives involved in transactions.
- **cities.csv** – Mapping of city names and country details.
- **countries.csv** – Country-level information.

---
## **Key Analyses Performed**
### **1️⃣ Data Cleaning & Preprocessing**
- Handled missing values in `SalesDate` and `CountryCode`.
- Fixed incorrect `TotalPrice` values by recalculating from quantity and price.
- Checked for duplicate entries and removed inconsistencies.
- Verified and corrected product-to-category mappings.

### **2️⃣ Supply Chain & Inventory Analysis**
- Identified **top-selling products** and their demand trends.
- Assessed **stock turnover rates** (if stock data is available).
- Evaluated **supplier and distribution efficiency**.

### **3️⃣ Logistics & Regional Performance**
- Analyzed **sales trends across different cities and countries**.
- Evaluated **average delivery times** (if delivery data was available).
- Identified **regions with high sales volume** to optimize supply chain strategies.

### **4️⃣ Sales & Customer Behavior Analysis**
- Ranked **top-selling categories** and compared them with top products.
- Identified **high-value customers** based on total purchase amount.
- Analyzed **monthly sales trends** to detect seasonality.
- Explored **profitability per product and category** (if cost data was available).

### **5️⃣ Forecasting & Business Recommendations**
- Used **time series forecasting (ARIMA)** to predict future demand.
- Recommended **inventory restocking strategies** based on demand trends.
- Proposed **marketing and promotional campaigns** based on high-demand products.

---
## **Key Insights & Findings**
📌 **Best-Selling Products:**
- The highest demand was for **Yoghurt Tubes, Chicken Wings, and Dried Fruits**.
- Demand was fairly evenly distributed among the top products.

📌 **Category Performance:**
- **Confections, Meat, and Poultry** were the most sold categories.
- Some **misclassified products** were identified (e.g., wine in "Dairy").

📌 **Regional Sales Trends:**
- Certain **cities and countries had significantly higher sales**, indicating key markets.
- Logistics analysis suggested **potential improvements in delivery times**.

📌 **Sales Trends & Seasonality:**
- Clear monthly fluctuations, with **peak sales periods** that can be leveraged for promotions.
- Demand forecasting predicted **upcoming high-demand periods**.

---
## **Next Steps & Recommendations**
✅ **Refine product categorization** to correct misclassified items.

✅ **Optimize inventory management** by prioritizing high-turnover products.

✅ **Enhance supplier relationships** to improve logistics in high-sales regions.

✅ **Leverage seasonal trends** for promotional strategies.

✅ **Further forecasting** to improve future demand predictions.

---
## **How to Reproduce This Analysis**
1. Clone the repository and download the dataset.
2. Install dependencies: `pip install pandas matplotlib numpy statsmodels`
3. Run the analysis scripts in **Google Colab** or a local Python environment.
4. Explore insights and visualizations in the Jupyter notebook.

---

🚀 **Thank you for exploring this analysis! Feel free to reach out with any suggestions or questions.**

