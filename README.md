💊 Pharmacy Sales & Profitability Dashboard (Power BI)
An interactive 4-page Power BI dashboard that analyzes sales and profit for a European pharmacy chain: where the money comes from, what sells, and what drives margin.
🔗 LinkedIn post: https://lnkd.in/p/dGAJ72Q2

📸 Dashboard Preview
Overview
<img width="1920" height="1078" alt="01_overview" src="https://github.com/user-attachments/assets/48bb69ef-6864-4666-b0eb-62c6e3c083b3" />

Geography
<img width="1920" height="1079" alt="02_geography" src="https://github.com/user-attachments/assets/c32d581d-86f7-415f-99dc-4a178fe2c3e5" />

Product & Category
<img width="1919" height="1079" alt="03_product_category" src="https://github.com/user-attachments/assets/6d7c2d8f-0e86-42cc-bf50-a5d7ec1ba40d" />

Profitability Drivers
<img width="1917" height="1076" alt="04_profitability" src="https://github.com/user-attachments/assets/19bae654-9aa6-4963-ba78-0fe26ca2f814" />

---
❓ Business Questions Answered
How much revenue and margin does the chain make, and is it growing?
Which countries, regions and pharmacies perform best?
Which product categories and brands bring the most revenue and profit?
Do promotions actually help profitability?
Does store type or store size change margin?

---
🔍 Key Insights (2025 view)
💶 €4.41M revenue and €1.24M margin (28.11%) from 227,991 units across 31,827 transactions
🌍 Lombardy, Hamburg and Utrecht are the top 3 regions by revenue
💊 Prescription brings the most revenue (€1.44M) but has the lowest margin among categories, while Wellness and Personal Care earn the highest
🏷️ Promotions cut margin: promo sales earn 19.96% vs 29.04% without promos
🧬 Branded products earn 28.50% margin vs 25.76% for generics
🏪 Margin stays near 28% across Urban, Suburban and Rural stores, so what is sold matters more than where
🚫 35 discontinued products still brought in €1.57L revenue in 2025
> Use the \*\*Year\*\* slicer to switch between 2024 and 2025. Numbers above are for 2025.

---
🛠️ Tools & Skills Used
Power BI Desktop: dashboard design, slicers, custom navigation
DAX: measures such as Total Revenue, Total Margin, Margin %, ranking (RANKX)
Data Modeling: star schema (1 fact table + 3 dimension tables)
Excel: source dataset

---
🗂️ Data Model
Table	Type	Rows
FactSales	Fact	62,139
DimDate	Dimension	731
DimPharmacy	Dimension	120
DimProduct	Dimension	220
---
📁 Repo Contents
```
├── README.md
├── Pharmacy\_Dashboard.pbix
├── Pharmacy\_Data\_Challenge\_Dataset.xlsx
└── screenshots/
```
▶️ How to Open
Download `Pharmacy\_Dashboard.pbix`
Open it in Power BI Desktop (free)

---
👤 Author
Darshan Vaghela | Aspiring Data Analyst
🔗https://www.linkedin.com/in/darshanvaghela9/ | 💻https://github.com/DarshanVaghela97/
