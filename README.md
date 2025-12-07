📊 Sales Analysis Dashboard — Power BI + Excel + GitHub Copilot
🔍 Overview

This project delivers a Sales Intelligence Dashboard to help business leaders make smarter decisions using data-driven insights.
The dashboard visualizes key performance metrics derived from Excel data and modeled in Power BI with customized DAX calculations.

This project demonstrates strong capabilities in:
✔ Data Cleaning & Modeling
✔ Data Visualization & Storytelling
✔ DAX-Based Analytical Logic
✔ AI-Assisted BI Development (GitHub Copilot + VS Code)

✨ Key Business Insights

📈 Track Net Revenue & Total Sales Performance
🎯 Identify Top-Performing Categories
🌍 Compare Regional Revenue Contributions
🧍 Customer Growth Trend Analysis
⚡ Instant Decision-Making with Dynamic Filters

🧰 Tech Stack
Category	Technology
Data Source	Excel (.xlsx)
BI Tool	Power BI Desktop
Analytics	DAX Measures
AI Assistance	GitHub Copilot in VS Code
Version Control	GitHub
🛠 Workflow

Excel → Power BI → Data Modeling → DAX Measures → AI-Assisted Optimization → Dashboard Insights

All measures were developed using Visual Studio Code with GitHub Copilot for:
✔ Faster development
✔ Cleaner formula logic
✔ Better coding standards

🧠 Core DAX Measures
Net Revenue = SUM('fact_sales'[Revenue])
Total Sales = SUM('fact_sales'[Sales])
Customer Count = DISTINCTCOUNT('dim_customers'[CustomerID])
Total Quantity = SUM('fact_sales'[Quantity])


Additional measures included inside .pbix file.

📊 Dashboard Preview
Insights Visualized	Screenshot
Revenue KPIs, Category & Region Comparison	(Insert image path here)
Customer Trend & Quantity Distribution	(Insert image path here)

Add screenshots inside an /images folder for better presentation.

📂 Repository Structure
📁 PowerBI-Sales-Analysis
 ├── 📘 Sales_Analysis_Dashboard.pbix
 ├── 📊 Dataset.xlsx
 ├── 🖼️ images/
 └── 📄 README.md

🧩 Data Model Overview

A structured model connecting:

Fact Table: Sales

Dimensions: Customers, Products, Stores, Date

This ensures accurate filtering & aggregation across visuals.

🎯 Business Impact
Before	After
Manual analysis in Excel	Automated Power BI insights
No clarity in category success	Clear revenue breakdown
Limited regional visibility	Performance comparison by region
Slow reporting	Real-time analytics

Unlocking data as a decision-making asset 💡

👨‍💻 Author

Anmol Pratap Singh
Data Analytics | Business Intelligence | Power BI Developer

📩 Email: singhanmol9081@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/anmolpratapsingh431/

⭐ Support

If this project inspired or helped you →
Please star ⭐ this repository.
It motivates me to build and share more real-world BI solutions!
