# 📦 Amazon Sales Data Power BI Dashboard

An end-to-end business analytics project that visualizes Amazon global sales data, including Sales, Profit, Quantity, Shipping Costs, and Market performance. This dashboard helps analyze business operations, shipping modes, geographical distribution, and product categories.

---

## 📊 Project Overview
This project focuses on analyzing Amazon sales data collected from multiple regions using Power BI. The objective is to gain insights into revenue trends, profitability, and market behavior to support business decision-making.

The dashboard presents key KPIs and visual representations to understand:
- Total Sales Revenue
- Total Profit
- Total Quantity Sold
- Total Shipping Cost
- Market Comparison
- Category-wise Sales
- State & Country Insights
- Shipping Mode Impact

---

## 🛠 Technologies & Tools Used

| Tool / Technology | Purpose |
|-------------------|---------|
| Power BI Desktop | Data modeling & dashboard creation |
| Excel / CSV Dataset | Source Data |
| DAX | KPI calculations |
| Power Query | Data cleaning & transformations |

---

## 🧾 Dataset Information

| Column Name | Description |
|-------------|------------|
| Order ID | Unique order number |
| Order Date | Date of purchase |
| Country | Name of country |
| State | Region inside country |
| Category | Product category |
| Sub-Category | Product type |
| Sales | Total order value |
| Quantity | Count of items sold |
| Profit | Profit earned |
| Ship Mode | Delivery method |
| Market | Region (APAC, EU, US, LATAM, EMEA, Africa, Canada) |

---

## 📈 Key Metrics (KPIs)

| Metric | Value |
|--------|--------|
| Total Quantity | 178K |
| Total Sales | $12.64M |
| Total Profit | $1.47M |
| Total Shipping Cost | $1.35M |

---

## 📌 Dashboard Insights
- Standard Class shipping produces the highest number of orders.
- United States generates the highest revenue among all countries.
- Technology category contributes the highest share of sales.
- APAC and EU markets contribute a major portion of revenue.
- Sales vary significantly across states, useful for regional targeting.

---

## 🖼 Dashboard Preview
(Upload your dashboard image & rename accordingly)


---

## 🔧 Steps to Run the Project
### Option 1: Run using Power BI Desktop
- Download/clone this GitHub repository
- Open file **Amazon_Sales.pbix** using Power BI Desktop
- Connect or refresh data source
- Explore dashboard

### Option 2: Modify Data
- Open **Power Query** → Review transformations
- Add/remove new data in Excel file
- Refresh dashboard

---

## 🧮 DAX Measures Used
```DAX
Total Sales = SUM(Sales[Sales])
Total Profit = SUM(Sales[Profit])
Total Quantity = SUM(Sales[Quantity])
Total Shipping Cost = SUM(Sales[Shipping Cost])
```

## Business Questions Answered**
-Which market generates the highest revenue?
-Which shipping mode is most popular and profitable? 
-Which country contributes most to the sales? 
-Which category drives maximum profit? 

## Future Enhancements** 
-Adding forecasting models for sales trends 
-Implementing R / Python advanced analytics 
-Creating drill-through reports for regional markets

## Contributing** 
-Contributions are welcome! 
-Feel free to fork this repo, raise issues, or submit pull requests. 

## License** 
-This project is for learning and analysis purposes only. 

## Contact** 
-For collaboration or suggestions: 

📧 Email: lpunyakanthreddy.com 
📍 LinkedIn: https://www.linkedin.com/in/punyakanth-reddy-l-b74808396/
