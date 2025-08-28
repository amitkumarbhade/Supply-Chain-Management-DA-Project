# 📦 Supply Chain Analysis: Insights into Products, Suppliers, and Logistics  

## 📌 Project Overview  
This project explores a supply chain dataset with 100 records and 24 attributes.  
The aim is to understand **product performance, supplier efficiency, logistics operations, costs, and risks**,  
and generate actionable insights to improve supply chain decision-making.  

---

## 🎯 Objectives  
1. **Data Exploration**  
   - Explore production volumes, stock levels, order quantities, revenue, costs, and lead times.  
   - Assess shipping costs, transportation modes, carriers, and routes.  
   - Evaluate supplier performance and product quality (inspection results, defect rates).  

2. **Visualization**  
   - Build informative visualizations to highlight relationships and distributions.  
   - Compare suppliers, carriers, transport modes, and products using charts and tables.  

3. **Insights & Recommendations**  
   - Identify top revenue drivers.  
   - Highlight supplier and logistics inefficiencies.  
   - Suggest actionable strategies for cost reduction, risk mitigation, and sustainability improvements.  

---

## 📊 Dataset  
- **Source:** Supply Chain dataset (synthetic, 100 rows)  
- **Records:** 100 supply chain transactions  
- **Features:** 24 attributes covering products, suppliers, logistics, costs, and quality  
- **Missing Values:** None  

### Key Columns  
- **Product type, SKU, Price** → product details  
- **Number of products sold, Revenue generated** → demand & revenue  
- **Stock levels, Production volumes, Order quantities** → inventory & production metrics  
- **Lead time, Lead times, Manufacturing lead time** → supply/manufacturing responsiveness  
- **Shipping times, Shipping costs, Shipping carriers** → logistics efficiency  
- **Supplier name, Manufacturing costs, Costs** → supplier performance and cost structure  
- **Inspection results, Defect rates** → quality and risk metrics  
- **Transportation modes, Routes, Location** → distribution and sustainability  

---

## 🔍 Project Steps  
1. **Data Overview** – structure, descriptive statistics, KPIs  
2. **Exploratory Data Analysis (EDA)** – distributions & relationships (cost vs revenue, price vs manufacturing cost, stock vs lead time)  
3. **Business Visualizations** –  
   - Revenue by product type & location  
   - Costs by supplier & inspection result  
   - Orders by transport mode  
   - Shipping costs by carrier  
   - Production by location  
   - Transportation route frequency  
   - Avg defect rate & lead time by product  
   - Supplier performance metrics  
4. **Risk & Sustainability** – defect rates, inspection results, emissions proxy (Air > Road > Rail)  
5. **Insights & Recommendations** – summarize actionable findings  

---

## 💡 Key Insights  
- **Products:** Skincare drives the highest revenue; cosmetics have higher defect rates.  
- **Suppliers:** Supplier 5 is the weakest performer (high costs, defects, long lead times); Supplier 1 is the most efficient.  
- **Logistics:** Carrier B delivers faster and cheaper; Route B is costlier than A/C.  
- **Geography:** Mumbai and Kolkata lead in production and orders.  
- **Sustainability:** Air transport is least sustainable (proxy); Rail is most efficient.  

---

## 🏆 Conclusion  
This analysis shows that supply chain performance is influenced by **product mix, supplier efficiency, and logistics choices**.  
Key recommendations include:  
- Optimize carrier selection (favor Carrier B for speed and cost).  
- Shift volume away from Route B where possible.  
- Audit Supplier 5 and improve or dual-source.  
- Align inventory levels with lead time variability.  
- Track sustainability with real emissions data; minimize reliance on Air freight.  

---

## 🚀 How to Run  
You can run the notebook directly in **Google Colab** (no setup required):  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amitkumarbhade/Supply-Chain-Management-Analysis/blob/main/Supply_Chain_Management_Analysis.ipynb)  

Steps:  
1. Upload the notebook (`Supply_Chain_Analysis.ipynb`) to Colab.  
2. Upload the dataset file (`supply_chain_data.csv`) when prompted.  
3. Run cells sequentially to reproduce the analysis and visualizations.  

---
