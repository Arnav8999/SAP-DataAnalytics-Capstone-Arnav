============================================================
  CAPSTONE PROJECT – SAP DATA ANALYTICS ENGINEER
  Sales Performance Analytics Dashboard
  RetailEdge India Pvt. Ltd.
============================================================

Student   : Arnav Singh
Roll No   : 2330221
Program   : B.Tech
Course    : SAP Data Analytics Engineer
Batch     : 2023 – 2027
Submitted : April 21, 2026

------------------------------------------------------------
PROJECT OVERVIEW
------------------------------------------------------------
This project implements an end-to-end SAP Data Analytics
solution for RetailEdge India Pvt. Ltd., a retail company
with 320 stores across India. The solution consolidates
2.5 million annual sales transactions into a real-time
Sales Performance Dashboard using SAP BW/4HANA and
SAP Analytics Cloud (SAC).

------------------------------------------------------------
ARCHITECTURE LAYERS
------------------------------------------------------------
Source     : SAP S/4HANA (Transactional ERP)
Staging    : SAP BW/4HANA PSA (Persistent Staging Area)
ETL        : BW DataSources + Transformations + DTP
Data Store : Advanced DSO (ZSALES_ADSO)
Model      : CompositeProvider (star schema)
Dashboard  : SAP Analytics Cloud (SAC) – Live Connection

------------------------------------------------------------
KEY INFOOBJECTS
------------------------------------------------------------
ZSALES_REG   – Sales Region (Characteristic)
ZSTORE_ID    – Store ID (Characteristic)
ZMAT_ID      – Material/Product ID (Characteristic)
ZCAL_MONTH   – Calendar Month (Time Characteristic)
ZNET_SALES   – Net Sales Value INR (Key Figure)
ZGROSS_MARGIN– Gross Margin INR (Key Figure)
ZUNITS_SOLD  – Units Sold (Key Figure)
ZSALES_TARGET– Monthly Sales Target (Key Figure)

------------------------------------------------------------
KPIs DELIVERED
------------------------------------------------------------
- Total Net Revenue vs Target (% variance)
- Monthly Sales Trend (12-month line chart)
- Regional Sales Heatmap (India Geo Map in SAC)
- Top 10 Products by Revenue
- Gross Margin % by Region and Product
- Store Performance Rankings (320 stores)

------------------------------------------------------------
FILES IN THIS ZIP
------------------------------------------------------------
1. SAP_DataAnalytics_Project_ArnavSingh.pdf  — Full project report
2. README.txt                                 — This file

------------------------------------------------------------
TECH STACK
------------------------------------------------------------
- SAP S/4HANA (Source ERP)
- SAP BW/4HANA 2.0 (Data Warehouse)
- SAP HANA In-Memory Database
- SAP Analytics Cloud (SAC) – Dashboard
- BW DataSources, Transformations, DTP
- ABAP Routines for transformation logic

------------------------------------------------------------
DECLARATION
------------------------------------------------------------
I hereby declare that this project is my own original work
prepared as part of the SAP Data Analytics Engineer
Capstone Project at KIIT School of Management.

============================================================
