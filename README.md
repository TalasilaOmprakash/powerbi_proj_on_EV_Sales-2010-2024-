🌍 Global Electric Vehicle Sales Analysis (2010–2024) ⚡
This project is about conducting an extensive analysis of global electric vehicle (EV) sales across regions, categories, and powertrain types from 2010 to 2024. It highlights adoption trends, growth patterns, and key insights into the EV market worldwide.

📝 Table of Contents
- Objective
- My Tasks
- Dataset Assessment
- Technologies Used
- Data Model View
- Dashboard Overview
- Calculated Metrics Used
- Key Insights & Recommendations
- Key Learnings

🎯 Objective
The goal of this project is to analyze global EV adoption trends and identify growth opportunities across regions and categories. By leveraging Power BI, the project provides insights into EV penetration, powertrain preferences (BEV, PHEV, FCEV), and regional disparities, supporting strategic decision‑making for sustainable transportation.

📌 My Tasks
As a data analyst, my responsibilities included:
- Developing appropriate metrics tailored to business questions.
- Building dashboards that provide intuitive and interactive visualizations.
- Identifying supplementary insights beyond the initial requirements.
- Integrating external research to contextualize findings and recommendations.

🔍 Dataset Assessment
The dataset includes the following key attributes:
- Region: Geographic area or country
- Category: Vehicle type (Cars, Buses, Trucks, 2‑Wheelers, etc.)
- Parameter: Metric (Stock, Sales, Energy Use, etc.)
- Powertrain: BEV, PHEV, FCEV
- Mode: Passenger, Freight, etc.
- Year: Calendar year (2010–2024)
- Unit: Measurement unit (Vehicles, TWh, etc.)
- Value: Numeric measurement

🔨 Technologies Used
- Microsoft Power BI – Data modeling, cleaning, and dashboard creation
- DAX – Advanced calculations and measures
- PowerPoint – Presenting insights to stakeholders

🗂️ Dashboard Link
"C:\Users\ompra\OneDrive\Desktop\powerbi proj\ev project final.pbix"

📊 Dashboard Overview
- 🌐 Global Overview – Total EVs, Growth %, Top Regions, BEV Share
  <img width="1317" height="727" alt="Screenshot 2025-10-17 003254" src="https://github.com/user-attachments/assets/dd2d84a4-d0b4-4208-b84f-2b8b51bd32de" />
- 🗺️ Regional & Category Trends – EV growth by region and category
  <img width="964" height="528" alt="Screenshot 2025-10-17 003512" src="https://github.com/user-attachments/assets/d55da38e-6395-4049-8300-cdccbf35fca3" />
- ⚡ Powertrain Insights – BEV vs PHEV comparison and growth trends
  <img width="955" height="528" alt="Screenshot 2025-10-17 003818" src="https://github.com/user-attachments/assets/ea9344e4-a6bd-43b8-a1f1-0a3d3e1672dc" />
- 📈 Parameter Analysis – Sales, Stock, Energy Consumption patterns
  <img width="1309" height="743" alt="Screenshot 2025-10-17 003952" src="https://github.com/user-attachments/assets/512aaabe-6bc4-43d4-be6f-6046beb5366b" />
- ⏳ Time Series – Year‑over‑year growth and cumulative analysis
  <img width="1341" height="742" alt="Screenshot 2025-10-17 004206" src="https://github.com/user-attachments/assets/fb55106d-3719-40a6-a606-63c9fbd1ac21" />

💪 Calculated Metrics Used
- Total EV Value = SUM(EV_Data[value])
- EV Growth % = (CurrentYearValue – PrevYearValue) / PrevYearValue
- BEV vs PHEV Share = DIVIDE([BEV Value], [Total EV Value])
- Region Type = IF(Region IN {Europe, NorthAmerica, Japan, Korea}, "Developed", "Developing")
- Peak Year = CALCULATE(MAX(year), FILTER(EV_Data, [Total EV Value] = [RegionMax]))

🔍 Key Insights & Recommendations
- EV adoption accelerated rapidly after 2015, led by Europe, China, and North America.
- BEVs dominate since 2020, showing a shift from hybrids to full‑electric.
- Developed regions show higher EV penetration and infrastructure maturity.
- Developing regions have strong potential with policy support and incentives.
- Energy use growth aligns with the increase in EV stock worldwide.
Recommendations:
- Expand BEV charging infrastructure.
- Encourage local manufacturing and battery recycling.
- Support R&D for better battery range and charging efficiency.
- Promote EV adoption in developing regions through incentives and awareness.

📢 Key Learnings
- Built interactive dashboards with slicers, filters, and drill‑downs.
- Applied dynamic ranking (Top‑N analysis) for regions and categories.
- Designed intuitive navigation with bookmarks and buttons.
- Used tooltips for enhanced visualization and context.
- Organized measures into folders for clarity and scalability.
- Focused on consistent color palettes and design aesthetics.
- Delivered insights through a structured PowerPoint presentation.
