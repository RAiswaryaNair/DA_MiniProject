# Data Co Supply Chain Analysis
# Overview
The DataCo Supply Chain project is a mini data analysis assignment that demonstrates end-to-end data processing and business intelligence using Microsoft Power BI. The raw dataset is a CSV file containing over 180,000 supply chain order records from 2015 to 2018 across multiple global markets.

The objective was to transform this raw data into an interactive, multi-page Power BI dashboard that gives business stakeholders clear, actionable insights across four key domains — executive performance, regional distribution, customer behavior, and shipping efficiency.

# Dataset Summary
* Source file: DataCoSupplyChain.csv (Kaggle Supply Chain dataset)
* Records: 180,000+ orders
* Time span: 2015 to 2018
* Markets: Europe, North America, Latin America, Africa, Asia, Oceania
* Tool used: Microsoft Power BI Desktop
* Preprocessing: Microsoft Excel — Power Query Editor
  
# Key Insights and Findings
***	Revenue & Profitability**
*	The business generated 115.2 million in discounted revenue across 639,000 orders from 2015 to 2018
*	80% of all orders (515K out of 639K) are profitable — a strong base performance
*	Revenue was stable from 2015 to 2017 then dropped sharply in 2018 — this decline affects every metric and requires investigation
*	Average profit per order peaked in 2017 at ~57 and fell to ~42 in 2018

***	Discounting Strategy**
*	At every discount level, significant average losses occur alongside profits
*	228,456 orders at High discount levels are still profitable — but 53,760 are making a loss
*	Discounting is not uniformly harmful but its impact varies significantly by product — the business needs product-level discount rules
*	Fan Shop and Apparel departments contribute the most to total profit (5.6M and 3.5M respectively)

***	Customer & Fraud**
*	Pittsburg has the highest fraud rate at ~20% — 1 in 5 orders from that city is flagged
*	Western Europe has the highest absolute fraud count (~3K) — consistent with being the largest order region
*	Consumer segment drives 51.86% of all profitable orders
*	Mary Smith is the single highest-value customer with 87,366 orders and 15.6M in total sales

***	Shipping Performance**
*	First Class shipping — the premium option — has the highest late delivery risk at 95.32% High Risk
*	Standard Class is the safest option at only 38.07% High Risk and also handles the most volume (108K orders)
*	The AI Key Influencers visual confirmed: First Class increases late delivery likelihood by 2.04x, Second Class by 1.55x
*	The business should investigate its First Class fulfilment process or adjust its SLA windows.

# Tools & Technologies Used
* Power BI
* DAX
* Power Query
* Microsoft Excel

# Dashboard Screenshots
	# Executive Analysis
<img width="1344" height="752" alt="Executive_Analysis" src="https://github.com/user-attachments/assets/d038f5df-5b01-4105-ae41-793701237753" />

# Customer Analysis
<img width="1350" height="759" alt="Customer_Analysis" src="https://github.com/user-attachments/assets/2e984d75-27ce-4761-acb7-2e1a48150746" />
	
# Profit Analysis
<img width="1352" height="753" alt="Profit_Analysis" src="https://github.com/user-attachments/assets/cf09ddc6-6b70-4b8a-bea7-16d5ed4fdd2f" />

# Shipment Analysis
<img width="1351" height="759" alt="Shipment_Analysis" src="https://github.com/user-attachments/assets/75f759b4-5c7a-4267-820d-473c5457477d" />

# Learning Outcomes

Through this project, I gained hands-on experience in:

* Data preprocessing
* Data modeling
* DAX calculations
* Interactive dashboard development
* Business storytelling through visualization
* Dashboard UI/UX design principles


# Future Improvements

* Integration with SQL database
* Real-time dashboard refresh
* Mobile-optimized dashboard design


# Author

Aiswarya R Nair

Power BI | Data Analytics | Business Intelligence
