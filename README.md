# -Online-Retail-Sales
This project simulates a real-world business scenario where an analyst was tasked with helping the CEO and CMO of an online retail company understand

> **Project Type**: Job Simulation  
> **Platform**: Forage (Virtual Internship)  
> **Tool**: Microsoft Power BI  
> **Focus**: Data Cleaning • DAX • Visualization • Business Insights



## 🚀 Project Overview

This project simulates a real-world business scenario where an analyst was tasked with helping the CEO and CMO of an online retail company understand:

- 💰 Which products drive the most revenue  
- 🌍 How sales perform across countries  
- 📈 Monthly revenue trends  
- 👥 Customer base behavior

The raw data was cleaned, modeled, and visualized using **Power BI** with custom DAX measures and visuals.


## 📁 Dataset Summary

- **Source**: Forage Job Simulation (provided CSV file)  
- **Data Includes**:  
  - Invoice Numbers  
  - Product Descriptions  
  - Quantities & Unit Prices  
  - Invoice Dates  
  - Country & Customer IDs  

---

## 🧹 Data Preparation

- Removed null/missing values  
- Filtered out canceled transactions (negative quantities)  
- Created new columns:
  - `MonthYear` (for time series)
  - `MonthYearSort` (for chronological sorting)

---

## 🧮 DAX Measures

| Measure Name | Description |
|--------------|-------------|
| `Total Revenue` | `Quantity × UnitPrice` |
| `Customer Count` | `DISTINCTCOUNT(CustomerID)` |
| `Average Revenue per Customer` | `Total Revenue ÷ Customer Count` |

---

## 📊 Visualizations Created

- **Line Chart** – Monthly Revenue Trend  
- **Bar Chart** – Top Products by Revenue  
- **Map Visualization** – Revenue by Country  
- **Pie Chart** – Revenue Share by Country  


---

## 🧱 Final Dashboard Features

- Fully interactive and dynamic  
- Executive-level summary for decision-making  
- Easy to extend with more filters or drilldowns

---

## 🔗 Screenshots

[Dashboard Overview](https://1drv.ms/i/c/1FD9ADE682BC7C1B/EQSVdOXfqr9HolqrPJOtn_ABv-avASbj9weZ0hbWZka_vg?e=qdSZXM.png)

