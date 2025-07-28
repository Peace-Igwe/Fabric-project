# 📊 Unified Customer Data Platform with Microsoft Fabric

**Client:** Commercial Bank  
**Role:** Microsoft Certified Fabric Analytics Engineer Associate  
**Tools & Services:** Microsoft Fabric (Data Factory, Dataflows Gen2, Lakehouse, Real-Time Analytics, Power BI), Azure (ADLS, Synapse, Databricks, Stream Analytics), Salesforce, SAP, Firebase, Finacle

---

## 🧩 Project Overview

The bank needed to unify customer data across multiple systems—CRM (Salesforce), ERP (SAP), mobile (Firebase), and core banking (Finacle)—into a **Single Customer View (SCV)**. The goal:  
✔️ Empower data-driven decisions  
✔️ Simplify analytics workflows  
✔️ Enable **real-time insights**  
✔️ Centralize governance and cost control

---

## 🚧 Key Challenges

- Fragmented systems with different APIs (REST, Event-Driven, SOAP)
- Inconsistent formats, duplicates, and nulls across datasets
- Different stakeholder needs: marketing, compliance, operations
- High costs & complexity of running multiple analytics platforms
- No real-time visibility into customer actions

---

## 🛠️ Solution Using Microsoft Fabric & Azure

### 1️⃣ Data Ingestion & Storage
- Used **Fabric Data Factory** to connect to Salesforce, SAP, Firebase, and Finacle.
- Ingested raw data into **OneLake** via **Dataflows Gen2** for schema mapping and standardization.

### 2️⃣ Data Transformation
- Used Fabric pipelines to:
  - Remove nulls and duplicates
  - Standardize date formats
  - Harmonize schemas across all systems
- Created a **Lakehouse model** for unified data storage.

### 3️⃣ Integration & Modeling
- Merged datasets into a single SCV in the Lakehouse.
- Built semantic models using **Power BI DirectLake** for live, in-place queries.

### 4️⃣ Real-Time Analytics & Visualization
- Used **Real-Time Analytics (KQL)** in Fabric to stream customer events.
- Delivered **interactive dashboards** using **Power BI** for non-technical teams.

---

## 🎯 Results

- ✅ 360° customer visibility
- ⏱️ Time-to-insight reduced by 60%
- 📈 Real-time dashboards for marketing, support, and compliance
- 📊 Increased analytics adoption by business users
- 🔐 Centralized governance with integrated cost control

---

## 🔍 Architecture Summary

| Phase       | Description                                                                 | Tools Used |
|-------------|-----------------------------------------------------------------------------|------------|
| **Ingestion** | Data extracted from Salesforce, SAP, Firebase, Finacle                    | ADF, APIs  |
| **Storage**   | Staged raw data in centralized storage                                     | ADLS       |
| **Transformation** | Cleaned and structured with scalable Spark pipelines                 | Databricks |
| **Integration** | SCV created from unified datasets and loaded into ADLS                  | ADF        |
| **Batch Analytics** | Analysis using SQL & BI tools                                       | Synapse, SQL, Power BI |
| **Streaming Analytics** | Real-time monitoring and dashboards                            | ADX, ASA, Grafana |

---

## 📌 Business Impact

- Created a **single source of truth** for customer data
- Enabled both **batch and real-time analytics**
- Improved data quality, compliance, and reporting
- Scaled easily with Azure-native services and Fabric

---

## 📁 Files in This Repo
- `Fabric Engineering Portfolio.docx` – Full write-up
- `README.md` – Markdown summary for GitHub display

---

🔗 _Need help deploying a similar data architecture? I’m available for freelance and collaboration opportunities!_
