Overview
This Power BI dashboard delivers a comprehensive analytics solution for the Electric Vehicle (EV) industry, covering global sales performance, gigafactory production efficiency, battery raw material cost exposure, and worldwide charging infrastructure readiness.
The report is built following BI best practices with a clean star schema, optimized DAX measures, reusable dimension tables, and modern field parameter interactivity for dynamic KPI and Axis switching.

Business Questions
This project answers the following core questions:

Which EV producers lead the global market?
How are EV sales evolving across different regions and countries?
How efficient are gigafactories (scrap rate, utilization, output)?
How do raw materials and suppliers impact battery costs?
How developed is the global EV charging infrastructure?
What are the YoY and Rolling 12‑month trends across key KPIs?
How does performance change across Producers, Regions, Countries, and Models?

Key Insights
Top EV producers dominate >60% of global market share.
Gigafactory scrap rate significantly affects cost per MWh.
Asia-Pacific leads in fast‑charging infrastructure development.
Raw material cost exposure is concentrated in four major materials.
Rising R12 units show year‑over‑year acceleration in EV adoption.
Charging networks remain uneven across regions, impacting market expansion.

Data and Modeling
The dataset consists of four fact tables and several supporting dimension tables. Data is cleaned and transformed using Power Query, with column normalization for:
Percentage fields
Material cost per ton
Date hierarchies
Gigafactory performance metrics

Relationships follow a Star Schema for high-performance analytics.

Data Model

Fact Tables:
EV_Sales
Gigafactory_Production
Battery_Raw_Materials
Charging_Infrastructure

Dimension Tables:
DimProducer
DimCountry
DimRegion
DimModel
DimFactory
DimSupplier
DateTable

Field Parameter Tables:
KPI Selector
Axis Selector

DAX Highlights

Tools Used
Power BI Desktop (2025+ dynamic parameters)
Power Query
DAX (Data Analysis Expressions)
Star Schema modeling
Custom Tooltips
Field Parameters
Drillthrough navigation

Files Included
EV_Industry_Analytics.pbix — full Power BI report
/screenshots — images of each report page
README.md — project documentation
(optional) Model_DAX.txt — exported DAX measures
