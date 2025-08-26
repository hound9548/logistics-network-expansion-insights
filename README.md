# 📦 Supply Chain Network Expansion Insights

This project analyzes logistics performance data to generate insights on **which facilities/regions are best suited for network expansion**. The analysis focuses on balancing **reliability (OTS: On-Time Shipment), capacity (Inbound & Outbound), and cost efficiency (VCPU: Variable Cost Per Unit)** to guide data-driven decision-making.

> _To ensure everyone can access the analysis, I have prepared it in both Excel and Tableau. If you don't have a Tableau subscription, don't worry. I have used both the normal formula method and the pivot table in Excel, and I've attached the workbook here._

## 🔍 Objectives

From the provided datasets, this project aimed to:

1. Calculate **Average OTS by Site** over the reporting period
2. Calculate **Average OTS by Region**
3. Determine **Total Outbound Capacity by Region**
4. Determine **Total Inbound Capacity by Region**
5. Calculate **Average VCPU by Region**
6. Combine results to identify **which regions are most suitable for expansion**

## 📊 Key Insights

The **West Coast** emerges as the strongest candidate for expansion with low VCPU, high OTS, and large capacity.
The **Southeast** is the second-strongest hub, with high capacity and stable performance at moderate cost.
The **Northeast** has strong capacity but is expensive, so expansion should be selective.
**Texas and the Midwest** require performance and cost improvements before scaling further.
At the site level, outliers such as SWA\_WAY, RYD\_FTW, and FFE\_TEX need targeted fixes to prevent dragging down regional averages.

## 🛠️ Tools & Methods

Excel Pivot Tables were used for aggregating site and region-level performance.
Tableau was used to create graphs and charts visualizing OTS, capacity, and cost comparisons.
Canva was used to design a polished presentation deck by integrating Tableau visualizations.
GitHub was used for version control and sharing results.

## 📂 Repository Structure

```
data/                Raw and processed datasets  
excel/               Pivot table analysis  
tableau/             Tableau workbook  
visuals/             Charts & dashboards exported  
presentation/        Final presentation deck (PDF/PPTX from Canva)  
README.md            Project overview  
```

## 🔮 Future Scope / Expansion

Build an interactive Tableau dashboard to provide real-time monitoring of OTS, cost, and capacity by site and region.
Incorporate scenario analysis to model how changes in cost or capacity affect expansion decisions.
Integrate demand forecasting to align facility expansion decisions with future market needs.
Explore resilience strategies such as risk pooling and multi-hub optimization to strengthen the logistics network.

## 🤝 Acknowledgment

This project was completed as a **data challenge** to demonstrate my analytical approach to solving real-world logistics and supply chain network optimization problems.

⚡ *If you’d like to collaborate or discuss supply chain analytics and network optimization, feel free to connect with me!*
