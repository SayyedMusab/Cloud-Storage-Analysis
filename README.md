# ☁️ Cloud Infrastructure Cost & Performance Optimization Analysis

## 📊 Project Overview
Modern enterprises face significant challenges in managing cloud infrastructure costs and performance due to dynamic workloads and unoptimized resource allocation.  
This analysis identifies **resource inefficiencies** and provides **data-driven strategies** to optimize cloud spending while maintaining performance across **CPU and storage resources**.

---

## 🎯 Business Objectives
- Identify resource inefficiencies leading to unnecessary cloud spending  
- Optimize CPU and storage utilization across cloud services  
- Quantify optimization potential and cost-saving opportunities  
- Deliver actionable insights for improved resource management  

---

## 📁 Dataset Overview

| Category | Key Columns |
|-----------|--------------|
| Domain | IT |
| **Usage Metrics** | Required CPU Hours, Actual CPU Hours, CPU Utilization %, Storage Used GB |
| **Financials** | Storage Cost $, Compute Cost $, Network Cost $, Total Cost $ |
| **Operations** | Cloud Service, Region, Owner Team, Project Type, Service Category |
| **Timeline** | Start Date, End Date |
| Source | Kaggle |
| Original Format	 | CSV (52,675 rows)   |


---

## 🛠️ Technical Approach

### Data Processing Pipeline
- **Data Cleaning:** Standardized values in *Project Type*, *Cloud Service*, and *Service Category*  
- **Missing Value Treatment:** Applied forward fill and median/mode imputation strategies  
- **Feature Engineering:** Created CPU performance and storage efficiency metrics  

---

## 📈 Key Findings

### 💻 CPU Utilization Analysis
- 68% of CPU resources are **under-provisioned** (up from 53% YoY)  
- **6,789 excess hours** of unmet CPU demand identified  
- Critical performance risks in **Analytics** and **E-Commerce** workloads (15–20% impact)  

### 💾 Storage Utilization Analysis
- 23% **over-provisioning** in production projects  
- **35K GB** wasted storage across top 10 projects alone  
- **$135K+** in excess storage costs identified  

### 💰 Financial Impact
- **Total Cloud Spend:** $2.89M (15% YoY increase)  
- **Identified Savings Potential:** $350K–$450K annually  
- **Optimization Opportunity:** 14% of total cloud spend  

---

## 📊 Dashboard Features

### 🧭 Interactive Analytics
- **Time Intelligence:** Two-year historical analysis with dynamic period selection  
- **Multi-dimensional Filtering:** Cloud services, project types, service categories  
- **Cross-filtering:** All visualizations interconnected for comprehensive analysis  

### 📉 Visualization Components
- **Pie Charts:** Segment distribution analysis  
- **Clustered Bar Charts:** Cost distribution across optimization categories  
- **Stacked Bar Charts:** Resource provisioning patterns by project type  

---

## 🚀 Business Impact

### Immediate Opportunities
- Right-sizing recommendations for over-provisioned resources  
- Capacity planning for under-provisioned workloads  
- Automated scaling implementation strategies  

### Strategic Value
- **$100K quarterly loss prevention** through performance optimization  
- **25–35% waste recovery** in DevOps and Database Migration projects  
- Enhanced performance for critical business workloads  

---

## 🛠️ Tech Stack
- **Data Processing:** Excel, Power Query  
- **Analysis:** Advanced Excel Formulas, Pivot Tables  
- **Visualization:** Interactive Dashboards, Slicers  
- **Documentation:** Markdown, Business Reporting  

---


Password : 4321
⭐ *If you find this project helpful, consider giving it a star on GitHub!*
