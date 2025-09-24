# 📊 Northwind Traders Performance Report

This project presents an **end-to-end Business Intelligence solution** built with **Power BI**, using the classic **Northwind Traders dataset**.  
It focuses on generating actionable insights for business stakeholders through interactive dashboards and KPIs.

---

## 🚀 Project Overview

The **Northwind dataset** (11 relational tables, 4K+ records) was integrated, cleaned, and modeled in Power BI.  
The final report provides a **360° view of company performance**, covering revenue, profitability, customers, products, deliveries, and employee contributions.

**Key Performance Metrics:**
- 💰 **Total Revenue**: $1.4M
- 📈 **Net Profit**: $406.3K  
- 🛒 **Total Orders**: 830
- 👥 **Customers Served**: 89
- 📦 **Products Sold**: 2,155 units
- 🏢 **Employee Count**: 9
- 🌍 **Geographic Reach**: 5+ countries

---

## 📌 Report Pages & Features

### 1️⃣ Employee Performance Dashboard
```
![Employee Performance Dashboard](images\Employee_Performance.png)
```
**Key Features:**
- Revenue generation per employee analysis
- Order handling capacity by individual staff
- Profit contribution breakdown
- Performance ranking and comparison
- Employee efficiency metrics

**Insights:**
- Employee #4 leads revenue generation ($0.25M)
- Top performer handles 156+ orders
- Clear performance distribution across team

---

### 2️⃣ Delivery Performance Analytics
```
![Delivery Performance Analytics](images/delivery_performance.png)
```
**Key Features:**
- On-time vs late delivery tracking (95.54% on-time rate)
- Average delivery days trend analysis
- Shipper performance comparison
- Customer distribution per shipping provider
- Monthly delivery performance trends

**Insights:**
- 793 on-time deliveries vs 37 late orders
- 8-day average delivery time
- Consistent performance across shipping partners

---

### 3️⃣ Sales Performance Report
```
![Sales Performance Report](images/sales_performance.png)
```
**Key Features:**
- Top 5 products by units sold, revenue, and orders
- Bottom 5 products performance analysis
- Product category breakdown
- Revenue per product insights
- Sales volume comparisons

**Insights:**
- **Camembert Pierrot** leads in units (1577 sold)
- **Côte de Blaye** generates highest revenue ($150K)
- **Raclette Courdavault** most ordered product

---

### 4️⃣ Customer Analytics Dashboard
```
![Customer Analytics Dashboard](images/customer_analytics.png)
```
**Key Features:**
- Top 10 customers by order volume and revenue
- Customer segmentation (VIP, High Value)
- Geographic distribution analysis
- Product category preferences
- Customer lifetime value metrics

**Insights:**
- **QUICK** customer leads with 28 orders ($117K revenue)
- Strong customer base in USA (15 customers)
- Balanced distribution across product categories

---

### 5️⃣ Business Intelligence Overview
```
![Business Intelligence Overview](images/business_overview.png)
```
**Key Features:**
- Orders breakdown by category
- Monthly orders trend analysis
- Revenue distribution by country
- Category-wise revenue and order percentages
- Seasonal performance patterns

**Insights:**
- **Beverages** lead in orders (334 orders, 21.15% revenue)
- Peak performance in March-April period
- **USA** dominates revenue contribution
- Balanced category distribution

---

## 🛠️ Technical Implementation

### Data Model
- **11 interconnected tables** with proper relationships
- **Star schema design** for optimal performance
- **Data cleaning & transformation** using Power Query
- **Custom measures & calculated columns** in DAX

### Key DAX Measures
```dax
Total Revenue = SUM(Orders[OrderTotal])
Profit Margin = DIVIDE([Total Profit], [Total Revenue], 0)
On-Time Delivery Rate = DIVIDE([On-Time Orders], [Total Orders], 0)
Top Customer Rank = RANKX(ALL(Customers), [Customer Revenue], DESC)
```

### Interactive Features
- 🎛️ **Dynamic filtering** by Year, Category, Employee, Customer
- 📅 **Date range slicers** for temporal analysis
- 🔄 **Cross-filtering** across all visualizations
- 📱 **Mobile-responsive** design
- 🎨 **Modern gradient UI** with intuitive navigation

---

## 📊 Business Insights & Recommendations

### 🏆 Key Findings
1. **Employee #4** is the top revenue generator - consider replicating their approach
2. **95.54% on-time delivery** rate demonstrates operational excellence
3. **Camembert Pierrot** and **Côte de Blaye** are star products
4. **USA market** shows strongest performance potential
5. **Seasonal trends** indicate March-April peak periods

### 💡 Strategic Recommendations
- **Scale successful practices** from top-performing employees
- **Invest in top-performing products** for inventory optimization
- **Expand USA market** presence given strong performance
- **Seasonal planning** around March-April peak periods
- **Customer retention** programs for VIP segments

---

## 🔧 Installation & Usage

### Prerequisites
- Power BI Desktop (latest version)
- Northwind sample database
- Basic understanding of Power BI navigation

### Setup Instructions
```bash
# 1. Clone this repository
git clone https://github.com/yourusername/northwind-powerbi-dashboard.git

# 2. Navigate to project folder
cd northwind-powerbi-dashboard

# 3. Open the .pbix file in Power BI Desktop
# File: Northwind_Performance_Report.pbix
```

### Usage Guide
1. **Open** the .pbix file in Power BI Desktop
2. **Navigate** between pages using the bottom tabs
3. **Apply filters** using slicers and dropdown menus
4. **Interact** with visuals by clicking for cross-filtering
5. **Export** reports or publish to Power BI Service

---

## 📁 Project Structure
```
northwind-powerbi-dashboard/
│
├── data/
│   ├── northwind_database.xlsx
│   └── data_dictionary.md
│
├── images/
│   ├── employee_performance.png
│   ├── delivery_performance.png
│   ├── sales_performance.png
│   ├── customer_analytics.png
│   └── business_overview.png
│
├── reports/
│   ├── Northwind_Performance_Report.pbix
│   └── data_model_documentation.pdf
│
├── README.md
└── LICENSE.md
```

---

## 🎯 Skills Demonstrated

- **Data Modeling** - Star schema design, relationships, data integrity
- **DAX Programming** - Advanced calculations, time intelligence, ranking
- **Data Visualization** - Chart selection, color theory, UX/UI principles  
- **Business Intelligence** - KPI definition, executive reporting, storytelling
- **Power BI Mastery** - Advanced features, performance optimization
- **Stakeholder Communication** - Clear insights, actionable recommendations

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

## 🙏 Acknowledgments

- **Microsoft** for the Northwind sample database
- **Power BI Community** for inspiration and best practices
- **Open source community** for tools and resources

---

## 📞 Contact

**Your Name** - [@yourhandle](https://twitter.com/yourhandle) - your.email@example.com

**Project Link:** [https://github.com/yourusername/northwind-powerbi-dashboard](https://github.com/yourusername/northwind-powerbi-dashboard)

---

⭐ **Star this repository** if you found it helpful!
