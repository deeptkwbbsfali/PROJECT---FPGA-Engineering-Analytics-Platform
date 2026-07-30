# PROJECT---FPGA-Engineering-Analytics-Platform
End-to-end Engineering Analytics Platform transforming Vivado FPGA reports into structured datasets for SQL, Python, Excel, and Power BI analysis. Built KPIs, dashboards, and failure analytics to monitor timing closure, resource utilization, deployment readiness, and engineering performance.
# FPGA Engineering Analytics Platform

## Project Overview
 
During my Research Internship at DRDO–SSPL, I worked on designing a 60-second sequential stopwatch using VHDL on the Xilinx Artix-7 FPGA platform in Vivado. While developing the hardware, I realized that every design iteration generated a large amount of engineering data through simulation, synthesis, implementation, timing, resource utilization, and DRC reports.

Instead of treating these reports only as debugging outputs, I approached them from a data analytics perspective. I organized the engineering data into a structured dataset, analyzed trends across multiple design iterations, identified the major causes of failures, monitored timing closure and resource utilization, and developed KPIs to measure design progress and deployment readiness.

To make the analysis more meaningful, I designed an end-to-end analytics workflow where engineering reports are transformed into structured datasets, analyzed using SQL and Python, and presented through interactive Power BI dashboards. This project demonstrates how engineering data can support better decision-making by reducing manual report analysis, highlighting failure patterns, and tracking overall design performance throughout the FPGA development lifecycle.

---

## Business Problem

FPGA development produces multiple reports after every design iteration. Engineers usually review these reports manually to understand why a design failed or whether it is ready for deployment. As the number of iterations increases, this process becomes repetitive and time-consuming.

The objective of this project is to convert engineering reports into structured analytical data so that design quality, timing closure, deployment readiness, and failure trends can be monitored using data analytics techniques instead of manual report inspection.

---

## Project Objectives

- Build a structured engineering dataset from Vivado-generated reports.
- Analyze design performance across multiple FPGA iterations.
- Identify the most frequent failure categories.
- Monitor timing closure and resource utilization.
- Develop engineering KPIs for deployment readiness.
- Visualize engineering performance using Power BI dashboards.
- Support data-driven engineering decisions.

---

## Tech Stack

- SQL
- Python
- Microsoft Excel
- Power BI
- Vivado
- VHDL
- Xilinx Artix-7 FPGA

---

## Analytics Workflow

Vivado Reports → Excel/CSV → SQL Database → Python Analysis → Power BI Dashboard → Engineering Insights

---

## Skills Demonstrated

- Data Analysis
- SQL
- Python
- Excel
- Power BI
- Data Cleaning
- Data Modeling
- KPI Development
- Dashboard Design
- Data Visualization
- Root Cause Analysis
- Statistical Analysis
- Engineering Analytics

---

## Project Outcome

This project helped me understand that engineering reports are valuable sources of structured data. By applying data analytics techniques to FPGA design reports, I was able to organize engineering information into meaningful KPIs, identify performance trends, analyze failure patterns, and present engineering insights through dashboards. The same analytical workflow can be extended to other FPGA projects to support faster debugging, standardized reporting, and data-driven engineering decisions.
