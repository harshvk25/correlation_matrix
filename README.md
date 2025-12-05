Supply Chain Correlation Matrix Analysis

Author: 24ds2000078@ds.study.iitm.ac.in

🏢 Business Context

OptimalFlow Logistics is analyzing supplier performance data for a major automotive manufacturer.
The objective is to identify relationships between key supply chain metrics such as:

Supplier_Lead_Time

Inventory_Levels

Order_Frequency

Delivery_Performance

Cost_Per_Unit

Understanding these correlations helps optimize supplier selection, procurement planning, and cost management.

📈 Project Deliverables

This repository contains:

correlation.csv

Correlation matrix generated using Excel Data Analysis ToolPak

heatmap.png

Excel heatmap using Red–White–Green conditional formatting

README.md

Documentation of steps and workflow (includes author email)

🛠️ Excel Workflow (as required)
1. Load Dataset

Imported q-excel-correlation-heatmap.xlsx into Excel.

2. Enable ToolPak

File → Options → Add-ins → Manage Excel Add-ins → Analysis ToolPak

3. Generate Correlation Matrix

Data → Data Analysis → Correlation

Selected all five variables

Enabled “Labels in first row”

Output to new worksheet

4. Create Heatmap in Excel

Selected numeric correlation values

Home → Conditional Formatting → Color Scales

Applied Red → White → Green palette

Red = low correlation

Green = high correlation

5. Export Files

Saved correlation table as correlation.csv

Captured heatmap screenshot (400×400 to 512×512 pixels)

Saved as heatmap.png
