# IT Support Operations Dashboard (Power BI)

## 📌 Project Overview
This project presents an **IT Support / Helpdesk Operations Dashboard** built using Power BI, designed to monitor **ticket workload, backlog risk, and SLA performance** in an operational environment.

The dashboard is structured from an **executive-first perspective**, enabling operations managers to quickly identify workload pressure, backlog risk, and SLA breaches without navigating complex reports.

---

## 🎯 Business Objective
To provide a **decision-ready view** for IT support and operations teams that answers:

- How many tickets are currently in the system?
- Where is the operational backlog building?
- Which agents are under workload pressure?
- Which ticket priorities are breaching SLAs?

---

## 📊 Key Metrics & Insights
- Total Tickets
- Open Tickets
- Backlog Tickets (>3 Days)
- SLA Breach Percentage
- Agent-wise workload and backlog distribution
- SLA breach volume and rate by ticket priority

---

## 🧠 Dashboard Highlights
- **KPI-driven executive layout**
- **Agent workload and backlog risk visualization**
- **Priority-level SLA breach analysis**
- Interactive slicers for:
  - Date
  - Department
  - Ticket Priority
- Clean fact–dimension data model for scalability

---

## 🗂 Dataset Structure
The project uses a structured Excel dataset with multiple tables:

- **Tickets (Fact Table)**  
  Ticket-level data including status, priority, SLA, agent, and resolution time

- **Agents (Dimension)**  
  Agent reference data

- **Departments (Dimension)**  
  Department reference data

- **Date (Dimension)**  
  Calendar table for time-based analysis

---

## 🛠 Tools & Technologies
- Power BI Desktop
- DAX (CALCULATE, FILTER, DIVIDE, context-based measures)
- Excel (structured dataset)
- Star schema data modeling

---

## 📷 Dashboard Preview
![IT Support Operations Dashboard](Screenshots/IT_Support_Operations_Dashboard.png)

---

## 📈 Learning Outcomes
- Designed operations-focused KPIs instead of generic metrics
- Implemented backlog aging logic using calculated columns
- Built context-aware DAX measures for SLA monitoring
- Applied executive-first dashboard design principles

---

## 🚀 Use Case
This dashboard is suitable for:
- IT Support Teams
- Helpdesk Operations
- MIS & Service Operations
- Operations & Data Analyst roles

---

## 📬 Feedback
Feedback and suggestions are welcome.  
This project is part of a continuous progression toward analyst-level, decision-oriented dashboards.
