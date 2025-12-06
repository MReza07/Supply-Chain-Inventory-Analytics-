## 📦 Inventory & Supply Chain Management Analysis – Power BI Dashboard

## 📘 Project Overview

This Power BI dashboard provides a comprehensive analysis of inventory performance, warehouse utilization, transportation efficiency, and supply chain operations.
It is designed for supply chain managers, inventory planners, and operations teams to monitor KPIs, reduce stock risks, and improve fulfillment performance.

The dashboard uses a real-world dataset representing warehouse, inventory, sales, transportation, and backorder activities across multiple regions and product categories.

## 🎯 Objectives of the Analysis

Monitor warehouse utilization and storage efficiency

Evaluate inventory performance using DSI (Days Sales of Inventory) & Inventory Turnover Ratio

Analyze transportation cost by region & category

Track yearly sales trends and demand fluctuations

Identify bottlenecks through backorder status

Evaluate category-wise lead time and stock availability

Support data-driven decision making for efficient supply chain operations



## 🚀 Key Insights

🔹 1. Warehouse Utilization – 34.08%

Indicates unused storage capacity; opportunity to optimize warehouse space or consolidate inventory.

🔹 2. Days Sales of Inventory – 15.56 Days

Inventory is sold on average every 15.56 days—shows efficient turnover.

🔹 3. Inventory Turnover Ratio – 23.47

High turnover ratio suggests strong product movement and good demand.

🔹 4. Transportation Cost Highlights

East & West regions incur higher transportation expenses

Electronics and furniture categories contribute the most to logistics cost

🔹 5. Units Sold Trend

Significant spike from 55K (2020) to 192K+ (2023) showing strong growth in demand.

🔹 6. Lead Time by Category

Clothing & Furniture show higher lead times (~5K days equivalent values from dataset)

Electronics have the lowest lead time

🔹 7. Backorder Status

Majority of backorders fall under Fulfilled status

Pending & canceled orders require further attention

🔹 8. Inventory Level by Category

Electronics have the highest inventory, while accessories have the lowest stock available.



## 🧩 Dashboard Features


✔️ KPIs on Top Panel

Warehouse Utilization %

Days Sales of Inventory (DSI)

Inventory Turnover Ratio

✔️ Interactive Filters

Region

Category



✔️ Visual Analytics

Gauge chart for utilization

Bar charts for transportation cost & backorders

Line chart for yearly sales

Donut chart for lead time

Inventory Level comparison chart



## 📂 Project Structure

Supply-Chain-Inventory-Analytics
│
├── 📄 Dataset/

│   └── Inventory_SupplyChain_Dataset.csv
│
├── 📄 Report/

│   └── Supply Chain & Inventory Analytics.pbix
│
├── 📄 Screenshots/

│   ├── Report.PNG

│   ├── KPI.PNG

│   ├── Transportation Cost By Region & Category.PNG

│   ├── Warehouse_Utilization.PNG

│
└── 📄 README.md


## 🛠️ Tech Stack & Tools

Power BI – Data modeling & dashboard development

Power Query – Data cleaning & transformation

DAX – Measures & KPI calculations

Excel/CSV – Data source

GitHub – Version control & project hosting



## 📊 DAX Measures Used

Warehouse Utilization = DIVIDE(SUM('Dataset'[Used_Space]), SUM('Dataset'[Total_Capacity]))

Days Sales of Inventory = DIVIDE(AVERAGE('Dataset'[Inventory_Value]), AVERAGE('Dataset'[Daily_Sales]))

Inventory Turnover Ratio = DIVIDE(SUM('Dataset'[COGS]), AVERAGE('Dataset'[Average_Inventory]))



## 🧠 Business Impact

This dashboard helps organizations:

Reduce excess stock & storage cost

Improve order fulfillment rate

Optimize transportation cost

Monitor high-value categories

Support operational decisions with real-time insights

Reduce lead time variances across categories




## 📄 How to Use This Project

Download the PBIX file

Open it in Power BI Desktop

Connect your own inventory/supply chain dataset (optional)

Refresh data & explore interactive dashboard

## 📜 License

This project is distributed under the MIT License.




## 👨‍💻 Author

Reazul Repon

Power BI & Data Analytics Enthusiast

SQL | Power BI | Python | Excel

Portfolio:https://github.com/MReza07

