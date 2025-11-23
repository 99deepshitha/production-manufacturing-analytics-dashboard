🏭 Production / Manufacturing Analytics Dashboard — Power BI Project
This project is an end-to-end Manufacturing Analytics Dashboard designed to monitor production output, downtime, machine performance, quality, and operator efficiency.
It is built using Power BI, DAX, Power Query, and Python (optional).

Project Objective
Provide actionable insights to answer key business questions:
- Which machines cause the most downtime?
- Which operators produce the highest output?
- Which shift has the worst defect rates?
- How does production trend over time?
- Which production line is most efficient?

📁 Dataset Structure
##### FACT_Production

| Column            | Meaning                        |
|-------------------|--------------------------------|
| Date              | Production date                |
| Machine_ID        | Unique machine identifier      |
| Shift             | Morning / Evening / Night      |
| Units_Produced    | Total units produced           |
| Units_Defective   | Total defective units          |
| Downtime_Minutes  | Total downtime                 |
| Operator_ID       | Operator assigned              |
| Production_Line   | Line A / B / C                 |


##### DIM_Machine
| Machine_ID | Machine_Name | Machine_Type |

##### DIM_Operator
| Operator_ID | Operator_Name | Experience_Level |

##### DIM_Date
Auto-generated in Power BI.

#### 📊Key KPIs
- Total Units Produced
- Total Downtime (Minutes)
- Downtime %
- Defect Rate
- OEE (Overall Equipment Effectiveness)
- Units per Shift
- Top 5 Machines by Output
- Worst 5 Machines by Downtime

📈 Dashboard Pages

📄 Page 1: Production Overview
- KPI Cards
- Daily production trend (Line chart)
- Units per production line (Bar chart)
- Defect rate by machine (Pie/Donut)
- Low-performing machine table
Slicers: Date, Machine, Shift, Line

📄 Page 2: Machine Performance
- Downtime by machine (Bar chart)
- Downtime heatmap (Shift × Machine)
- Defect trends (Line chart)
- Machine availability KPI

📄 Page 3: Operator Performance
- Output by operator (Bar chart)
- Experience level vs defect rate (Scatter)
- Best Operator KPI


🛠 Tech Stack
- Power BI Desktop
- DAX
- Power Query
- Star Schema Modeling

### 📥 How to Use This Project

1. Download the `.pbix` file.
2. Open it in **Power BI Desktop**.
3. Upload datasets (if required).
4. Refresh the model.


Dashboard Preview
[Production Overview](dashboard-production-overview.png)
[Machine Performance](dashboard-machine-performance.png)
[Operator Performance](dashboard-operator-performance.png)



