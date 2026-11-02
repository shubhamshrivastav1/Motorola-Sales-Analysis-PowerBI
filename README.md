
# 📱 Motorola Sales Analysis Dashboard | Power BI

<p align="center">
  <b>Interactive Business Intelligence & Data Analytics Project</b>
</p>

<p align="center">
  Transforming Mobile Sales Data into Meaningful Business Insights Using Microsoft Power BI.
</p>


---

## 📌 1. Project Overview

The **Motorola Sales Analysis Dashboard** is an interactive Business Intelligence project developed using Microsoft Power BI to analyze mobile sales performance and customer purchasing behavior.

The project focuses on transforming sales data into meaningful insights through data preparation, analysis, KPI development, and interactive data visualizations.

The dashboard provides a comprehensive overview of sales performance across different cities, mobile brands, mobile models, payment methods, customer ratings, and days of the week.

It helps users understand business performance, identify sales trends, compare product performance, and make data-driven decisions.

---

## ScreenShot of Dashboard


<p align="center">
  <img width="1380" height="747" alt="Screenshot 2026-11-02 210514" src="https://github.com/user-attachments/assets/d1ff1ee1-ec59-44cc-bb7a-a064690a8f10" />

</p>


## 🎯 2. Business Problem

Understanding sales performance across multiple products, cities, and payment methods can be challenging when dealing with large datasets.

Businesses need a centralized reporting solution to monitor important sales metrics and identify patterns in customer purchasing behavior.

This project addresses the following business questions:

- What is the overall sales performance?
- Which cities contribute to total sales?
- Which mobile brands generate higher revenue?
- Which mobile models perform better?
- How does sales quantity vary across months?
- Which payment methods are preferred by customers?
- How are customers rating their purchases?
- Which days generate higher sales?

---

## 🎯 3. Project Objectives

- Analyze overall mobile sales performance.
- Track total revenue, quantity, and transactions.
- Identify city-wise sales distribution.
- Compare brand-wise sales performance.
- Analyze mobile model performance.
- Understand monthly sales quantity trends.
- Evaluate customer rating distributions.
- Analyze payment method preferences.
- Identify day-wise sales patterns.
- Develop an interactive dashboard for business analysis.

---

## 🔄 4. Project Workflow

The project follows a structured data analytics workflow:

**Data Collection → Data Cleaning → Data Transformation → Data Analysis → DAX Calculations → Dashboard Development → Business Insights**

### Step 1: Data Collection

- Collected the mobile sales dataset.
- Examined the dataset structure and available columns.
- Identified important sales-related attributes.
- Reviewed fields required for business analysis.

### Step 2: Data Cleaning

Used Power Query to prepare the dataset for analysis.

Key activities:

- Checked for missing and blank values.
- Identified duplicate records.
- Reviewed data types.
- Checked inconsistent values.
- Removed unnecessary columns where required.
- Prepared the dataset for further analysis.

### Step 3: Data Transformation

Transformed the raw data into an analysis-ready format.

Key activities:

- Prepared date-related fields.
- Organized month and day name information.
- Standardized categorical fields.
- Prepared brand, city, and payment method attributes.
- Ensured data consistency for reporting.

### Step 4: Data Analysis

Performed sales analysis across multiple business dimensions:

- City-wise sales analysis.
- Monthly quantity analysis.
- Brand-wise sales comparison.
- Mobile model sales analysis.
- Customer ratings analysis.
- Payment method analysis.
- Day-wise sales analysis.

### Step 5: KPI & DAX Development

Used Power BI measures to calculate important business metrics.

Example DAX calculations:

**Total Sales**
```dax
Total Sales =
SUM(Sales[Sales])
```

**Total Quantity**
```dax
Total Quantity =
SUM(Sales[Quantity])
```

**Total Transactions**
```dax
Total Transactions =
DISTINCTCOUNT(Sales[Transaction ID])
```

**Average Sales**
```dax
Average Sales =
AVERAGE(Sales[Sales])
```

*Note: These are illustrative DAX formulas. Actual table and column names may differ depending on the dataset.*

### Step 6: Dashboard Development

Developed an interactive dashboard using Power BI visualizations.

The dashboard includes:

- KPI Cards
- Map Visualization
- Bar Charts
- Pie Chart
- Line Chart
- Funnel Chart
- Data Tables
- Interactive Slicers

### Step 7: Dashboard Testing

- Validated KPI calculations against the dataset.
- Tested interactive slicers.
- Checked chart interactions.
- Reviewed visual consistency.
- Verified dashboard filtering behavior.

---

## 📊 5. Key Performance Indicators (KPIs)

The dashboard displays four major business metrics.

| KPI | Dashboard Value |
|---|---:|
| Total Sales | 68M |
| Total Quantity | 2K |
| Total Transactions | 331 |
| Average Sales | 41K |

These KPIs provide a quick overview of overall mobile sales performance.

*Values are based on the dashboard screenshot with the displayed filter selection.*

---

## 📈 6. Dashboard Visualizations

### 1. Total Sales by City

- Displays geographical sales distribution across cities.
- Helps identify city-wise sales contributions.
- Uses map visualization for geographical analysis.

### 2. Total Quantity by Month

- Displays monthly quantity trends.
- Helps analyze sales volume across months.
- Supports month-wise performance analysis.

### 3. Customer Ratings

- Displays customer rating distribution.
- Helps understand customer feedback patterns.
- Provides a visual comparison of rating categories.

### 4. Transactions by Payment Method

Analyzes transaction distribution across:

- Credit Card
- Debit Card
- UPI
- Cash

Helps understand customer payment preferences.

### 5. Brand-wise Sales Analysis

Provides a detailed comparison of different mobile brands.

Metrics include:

- Total Sales
- Total Quantity
- Total Transactions

### 6. Total Sales by Mobile Model

- Compares sales across mobile models.
- Identifies high-revenue products.
- Helps understand product performance.

### 7. Total Sales by Day Name

- Displays day-wise sales performance.
- Helps identify sales patterns across weekdays.
- Supports business planning and performance analysis.

---

## 🎛️ 7. Interactive Dashboard Features

The dashboard includes interactive filters for dynamic analysis.

| Filter | Description |
|---|---|
| Mobile Model | Filter sales by mobile model |
| Payment Method | Analyze payment preferences |
| Brand | Compare different mobile brands |
| Day Name | Analyze weekday sales |
| Month Selection | Explore monthly performance |

Users can apply multiple filters to explore specific business scenarios and analyze the data from different perspectives.

---

## 💡 8. Business Insights & Analysis

The dashboard enables business users to explore important sales patterns.

Key analytical areas:

- Identify cities contributing to overall sales.
- Compare mobile brand performance.
- Understand customer payment preferences.
- Analyze mobile model revenue contribution.
- Evaluate customer rating distribution.
- Explore monthly quantity trends.
- Compare sales performance across weekdays.

### Business Applications

The analysis can support:

- Sales performance monitoring.
- Product performance evaluation.
- Marketing strategy planning.
- Inventory planning.
- Customer experience analysis.
- Business decision-making.

*Specific numerical business findings should be added after validating the complete dataset.*

---

## 🛠️ 9. Tools & Technologies

| Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | Measures and KPI calculations |
| Microsoft Excel | Dataset handling |
| Data Visualization | Business reporting |
| Git & GitHub | Project version control |

---

## 📂 10. Project Structure

```text
Motorola-Sales-Analysis-PowerBI/
│
├── Dashboard/
│   └── Motorola_Sales_Dashboard.pbix
│
├── Dataset/
│   └── Motorola_Sales_Data.xlsx
│
├── Screenshots/
│   └── dashboard-preview.png
│
└── README.md
```

---

## 🚀 11. How to Run This Project

Follow these steps to explore the dashboard:

1. Clone or download this repository.
2. Install Microsoft Power BI Desktop.
3. Open the `.pbix` dashboard file.
4. If required, update the dataset source path.
5. Refresh the dataset.
6. Explore the dashboard using interactive filters.
7. Analyze sales performance through different visualizations.

---

## 🔮 12. Future Enhancements

Potential improvements for this project:

- Year-over-Year (YoY) sales analysis.
- Month-over-Month (MoM) growth analysis.
- Sales forecasting.
- Profit and profit margin analysis.
- Sales target vs actual comparison.
- Advanced DAX calculations.
- Drill-through reports.
- Detailed customer segmentation.

---

## 👨‍💻 13. About the Author

**Shubham Shrivastav**

Full Stack Developer | Data Analytics 

📍 Mumbai, Maharashtra, India

### Technical Skills

- **Programming:** Java, Python, JavaScript, SQL
- **Data Analytics:** Power BI, Excel, Data Visualization
- **Frontend:** React.js, Redux, Tailwind CSS
- **Backend:** Node.js, Express.js, REST APIs
- **Database:** MongoDB, MySQL
- **Tools:** Git, GitHub, VS Code, Postman

### Education

- Master of Computer Applications (MCA) — MET, Mumbai
- Bachelor of Computer Science — S.K. Somaiya College, Mumbai

### Connect With Me

- GitHub: https://github.com/shubhamshrivastav1
- LinkedIn: https://www.linkedin.com/in/shubham-shrivastav-911078294/
- Email: ssk06112000@gmail.com

---

## ⭐ Support

If you find this project useful or interesting, consider giving this repository a star ⭐.

Your feedback and suggestions are always welcome!

<p align="center">
  <b>Thank You for Visiting My Project!</b>
</p>
