⚠️ **Confidential Code**: This repository does not include source code due to client confidentiality. It contains a high-level summary to demonstrate project scope and my technical contributions.

Voxel Supplier XML Automation is an end-to-end ETL solution built to automate the ingestion, validation, transformation, and reconciliation of daily vendor statements received in XML format from Voxel. The project was initiated to eliminate manual processing bottlenecks, improve financial accuracy, and meet strict reconciliation SLAs.

This solution features a hybrid architecture using SSIS + SQL Server for high-frequency processing and Azure Data Factory for scalable, cloud-native workloads. Monitoring and resolution interfaces were implemented using Power BI, Power Apps, and Power Automate, enabling business users to track and triage errors independently.

🚀 Key Features
Automated ingestion of 5000+ XML files per day.
Dynamic XML parsing using SQL OPENXML() and ADF Mapping Data Flows.
Business rule validations (M&E, Card, Duplicates, Recon, Payment).
Journal output generation for Blackline and AMOS systems.
File archiving based on status: Processed, Duplicate, Error.
Real-time dashboards with SLA metrics using Power BI.
Embedded UI for resolution via Power Apps.
Alerts and workflow automation using Power Automate.

🧰 Tech Stack
ETL Tools: SSIS, Azure Data Factory (ADF)
Database: SQL Server
Cloud Services: Azure Blob Storage, Azure Data Factory
Monitoring & UI: Power BI, Power Apps
Automation: Power Automate
File Transfer: SFTP, MFT
Version Control: Git

📈 Business Impact
Reduced manual reconciliation effort by 90%
Improved ingestion uptime to 99.9%
Cut reconciliation time from 24 hours to 1 hour
Scalable architecture ready for future cloud-first migration

