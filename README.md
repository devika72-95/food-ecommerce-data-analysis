# 🍔 Food E-Commerce Data Analysis | Excel

### 📌 Turning E-Commerce Data into Business Insights

## 🔍 Project Overview

This project focuses on analyzing food e-commerce and home delivery operations using Microsoft Excel.

The objective is to understand customer purchasing behavior, order completion, marketing acquisition performance, revenue patterns, discounts, delivery charges, and delivery efficiency.

Using Excel formulas, lookup functions, PivotTables, and data analysis techniques, this project transforms transaction data into meaningful business insights.

---

## 🎯 Business Objectives

- Understand order distribution across delivery areas and time slots.
- Identify monthly order growth patterns.
- Evaluate order completion rates.
- Analyze customer acquisition channels.
- Calculate Customer Lifetime Value (LTV).
- Understand revenue, discounts, and delivery charges.
- Evaluate delivery performance.
- Identify customer satisfaction patterns through ratings.

---

## 📂 Dataset Overview

The project workbook contains two primary data sheets:

**1. Transaction Data**
- 22,823 transaction records.
- Contains order-level information.
- Includes customer, delivery, payment, discount, and order details.

**2. Source Data**
- 3,750 customer records.
- Contains customer acquisition source information.
- Used to map customer IDs with acquisition channels.

**Dataset Period:** January 2021 – September 2021  
**Business Location:** Bangalore  
**Analysis Tool:** Microsoft Excel

*Note: The original external dataset source has not been independently verified.*

---

## 🧹 Data Cleaning & Preparation

The following data preparation activities were performed:

- Extracted date and time from order timestamps.
- Created separate Date and Order Time columns.
- Extracted Month and Day.
- Classified orders into Weekday and Weekend.
- Categorized orders into delivery time slots.
- Used VLOOKUP to map customer IDs with acquisition sources.
- Calculated order-to-arrival time.
- Calculated arrival-to-pickup time.
- Calculated pickup-to-delivery time.
- Calculated total order-to-delivery time.
- Created order completion flags.
- Calculated delivery charges as a percentage of product amount.
- Calculated discount percentages.
- Calculated final order amounts.

---

## 📊 Business Questions & Analysis

A total of 21 business questions were explored across four analytical areas.

### 1️⃣ Order-Level Analysis

- Order distribution by delivery slot and delivery area.
- Monthly order growth by delivery area.
- Delivery charges as a percentage of product amount.
- Discount percentage by delivery slot and month.
- Discount percentage by delivery area and slot.

### 2️⃣ Order Completion Analysis

- Completion rate by delivery slot and weekday.
- Completion rate by delivery area.
- Completion rate by number of products ordered.
- Identification of patterns in order completion.

### 3️⃣ Customer-Level Analysis

- Completion rate by acquisition source.
- Individual customer Lifetime Value (LTV).
- Aggregated LTV by acquisition source.
- Aggregated LTV by acquisition month.
- Average revenue per order by acquisition source.
- Average revenue per order by acquisition month.
- Order rating analysis based on delivery slots, product quantities, delivery charges, and discounts.

### 4️⃣ Delivery Analysis

- Average delivery time by month and delivery area.
- Delivery time comparison between weekdays and weekends.
- Average delivery time by delivery slot.
- Delivery charge patterns across delivery areas.
- Delivery time patterns across different delivery areas.

---

## 📈 Key Performance Indicators (KPIs)

The following KPIs were considered during the analysis:

- **Total Orders:** Total number of orders.
- **Completed Orders:** Successfully completed orders.
- **Completion Rate:** Completed Orders / Total Orders × 100.
- **Average Order Value:** Total Final Amount / Total Orders.
- **Customer Lifetime Value:** Customer-level revenue over the observed period.
- **Average Order Rating:** Average recorded customer rating.
- **Average Delivery Time:** Average order-to-delivery duration.
- **Average Delivery Charges:** Average delivery charges per order.
- **Discount Percentage:** Discount / Product Amount × 100.
- **Average Revenue per Order:** Revenue / Number of Orders.

---

## 💡 Key Business Findings

### 1. Order Performance

- Total orders analyzed: 22,823.
- Completed orders: 22,721.
- Cancelled orders: 102.
- Overall completion rate: approximately 99.55%.

### 2. Customer Acquisition

The leading acquisition sources by order volume were:

- Organic: 6,680 orders.
- Google: 5,348 orders.
- Offline Campaign: 2,862 orders.

Organic and Google were the two largest acquisition sources by order volume.

### 3. Delivery Area Performance

- HSR Layout: 15,657 orders.
- ITI Layout: 3,946 orders.
- Harlur: 1,309 orders.

HSR Layout recorded the highest order volume among the delivery locations.

### 4. Delivery Efficiency

- Average delivery time for completed orders was approximately 24.26 minutes.
- Late Night orders recorded an average delivery time of approximately 17.49 minutes.
- Afternoon orders recorded an average delivery time of approximately 25.78 minutes.

### 5. Revenue Analysis

- Total Final Amount: 7,963,632.
- Average Final Amount per Order: approximately 348.93.
- Average Product Amount per Order: approximately 352.31.

### 6. Customer Ratings

- Average order rating: approximately 4.85.
- Rating values were available for 17,103 records.

*Currency has not been independently confirmed, so no currency symbol is assigned.*

---

## 🚀 Business Recommendations

**Order Management**
- Allocate delivery resources according to order volume across delivery areas and time slots.

**Customer Acquisition**
- Evaluate acquisition channels using order volume, completion rates, and customer lifetime value.

**Delivery Optimization**
- Investigate delivery delays during afternoon and evening slots.

**Customer Retention**
- Identify high-value customers and develop customer retention strategies.

**Discount Optimization**
- Analyze discount patterns and their relationship with order completion and revenue.

**Delivery Cost Management**
- Monitor delivery charges across different areas and time slots.

**Customer Satisfaction**
- Use customer ratings and delivery performance to identify improvement opportunities.

---

## 🛠️ Tools & Technical Skills

**Microsoft Excel**
- Data Cleaning & Preparation
- VLOOKUP
- IF and Conditional Functions
- Date & Time Functions
- PivotTables
- PivotCharts
- Data Aggregation
- Percentage Calculations
- Customer Segmentation
- KPI Analysis
- Business Data Analysis

---

## 📁 Project Structure

```text
Food-E-Commerce-Data-Analysis/
│
├── Food E-Commerce Data Analysis.xlsx
│
└── README.md
```

*The raw Excel workbook is not included in the public repository at this stage.*

---

## 📝 Conclusion

This project demonstrates the practical application of Microsoft Excel in analyzing food e-commerce operations and customer behavior.

By analyzing 22,823 transaction records, the project explores order completion, customer acquisition, revenue patterns, delivery performance, discounts, and customer satisfaction.

The analysis highlights how Excel-based data preparation, calculations, and business reporting can support operational monitoring and data-driven decision-making.

---

## 👩‍💻 About the Author

**Devika Sutar**

Aspiring Data Analyst | Civil Engineering Graduate transitioning into Data Analytics.

**Technical Skills:** Microsoft Excel | SQL | Python | Power BI | Statistics
