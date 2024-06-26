# BUSINESS--INSIGHTS--360
🌟 Project Overview
AtliQ Hardware has been growing rapidly in recent years. To stay ahead of competitors and make data-driven decisions, they decided to implement data analytics using PowerBI. This project aims to address stakeholders' questions across various aspects like finance, sales, marketing, and supply chain.

I followed the Codebasics PowerBI Course for this project.

LIVE DASHBOARD LINK:
https://app.powerbi.com/groups/me/reports/90b713a5-2436-4f0b-9c18-b631745cc315?experience=power-bi&clientSideAuth=0


💻 Tech Stack

🐬 SQL

📊 PowerBI Desktop

📈 Excel

🧮 DAX language

⚡ DAX Studio (for optimizing the report)

📜 Project charter file

🛠️ PowerBI Techniques Learned

🧠 Key questions to ask before starting a project

🧮 Creating calculated columns

🔢 Creating measures using DAX language

🗂️ Data modeling

📑 Using Bookmarks to switch between visuals

🖱️ Page navigation with buttons

➗ Using the DIVIDE function to prevent zero division errors

📅 Creating a date table using M language

🏷️ Dynamic titles based on applied filters

📊 Using KPI indicators

🎨 Conditional formatting in visuals using icons or background color

✔️ Data validation techniques

🌐 PowerBI Services

🚀 Publishing reports to PowerBI Services

🔄 Setting up a personal gateway for automatic data refresh

📱 PowerBI App creation

🤝 Collaboration, workspace management, and access permissions in PowerBI Services
And more 😅

🐙 GitHub
📂 Uploading large files using GitHub LFS

🔍 Tracking specific file types for LFS

📚 Business Terms

💵 Gross price

📉 Pre-invoice deductions

🧾 Net invoice sale

📈 Post-invoice deductions

💲 Net sales

🏷️ COGS (Cost of Goods Sold)

💰 Gross margin

💸 Net profit

📆 YTD (Year to Date)

📅 YTG (Year to Go)

🛒 Direct

🏬 Retailer

📦 Distributors

👥 Consumer

🏢 Company Background

AtliQ Hardware has seen significant growth in recent years, expanding globally. The company sells computers and computer accessories through three channels:

🏬 Retailers

🛒 Direct

📦 Distributors

Recently, the company faced unforeseen losses by opening a store in America based on surveys, intuition, and some Excel analysis. Their competitors have analytics teams to make data-driven decisions, pushing AtliQ Hardware to build their analytics team for better insights and decision-making in the future.

❓ Key Questions Before Starting the Dashboard

❔ What is the objective of building this PowerBI dashboard?

📏 How will the success of this project be measured?

⏳ What is the project deadline?

👀 Do stakeholders expect a preview before the actual release?

💡 What are stakeholders' hopes for this project?

😟 What are stakeholders' fears regarding this dashboard?

👥 Who will use this dashboard and for what purpose?

🎯 What are stakeholders' expectations by the end of this project?

⚠️ What can go wrong during this project?

📄 What resources/data are needed to build this dashboard?

🖌️ Are there any stakeholder inputs regarding the dashboard's design and views?

🗄️ Dataset Understanding
Understanding available data is crucial before analysis. Familiarize yourself with the data:

Dimension Table: Contains static data like customer and product details.
Fact Table: Contains transaction data.
gdb041
dim_customer

🌍 27 distinct markets (e.g., India, USA, Spain)

👥 75 distinct customers across markets

🏢 2 types of platforms:

 Brick & Mortar - Physical/offline store
 E-commerce - Online store (Amazon, Flipkart etc.)
🛒 3 channels:

 Retailer
 Direct
 Distributors
dim_market

🌍 27 distinct markets

🌎 7 sub-zones

🌏 4 regions: APAC, EU, NAN, LATAM
dim_product

🏷️ Divisions:
 P&A (Peripherals, Accessories)
 
 PC (Notebook, Desktop)
 
 N&S (Networking, Storage)
 
🛍️ 14 different categories (e.g., Internal HDD, keyboard)

📦 Various product variants

fact_forecast_monthly

🔮 Forecasts customer needs to improve satisfaction and reduce warehouse costs
🗃️ Denormalized by the data engineering team for analytical use

📅 Monthly data with forecast quantities
fact_sales_monthly

💹 Similar to fact_forecast_monthly but includes sold quantities
gdb056
freight_cost

🚚 Travel and other costs per market with fiscal year
gross_price

💲 Gross prices with product codes
manufacturing_cost

🏭 Manufacturing costs with product codes and year
pre_invoice_deductions

💸 Pre-invoice deductions percentage per customer with year
post_invoice_deductions

💰 Post-invoice deductions details
📥 Importing Data into PowerBI
Import datasets from the MySQL database into PowerBI using the provided database access credentials.

🗂️ Data Model
Data modeling is crucial for report performance. Poor modeling can negatively impact the report. Follow good data modeling practices, such as those outlined here. This project uses the Snowfall data modeling method.

Data Model

🎨 Dashboard Design
Based on the received mock-ups, the team will design visuals and create measures as needed.

🏠 Home View
The Home view contains buttons to navigate to specific views:


ℹ️ Info
💵 Finance View

📈 Sales View

📊 Marketing View

🚚 Supply Chain View

👔 Executive View

💬 Support

To view the data model click on the [LIVE DASHBOARD LINK](https://app.powerbi.com/groups/me/reports/90b713a5-2436-4f0b-9c18-b631745cc315?experience=power-bi&clientSideAuth=0).

