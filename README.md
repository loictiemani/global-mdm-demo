# global-mdm-demo
Global Master Data Management Simulation for Chart of Accounts (CoA)


🌐 Project Title:
Global Master Data Management Simulation for Chart of Accounts (CoA)

🎯 Objective:
Simulate a real-world MDM workflow focused on Chart of Accounts (CoA) lifecycle and transformation, aligned with transitioning from a legacy ERP to a cloud-based system (OneCloud analog). The project includes SQL-based transformations, data validation rules, and cross-functional data integration.

📌 Features
🔢 CoA Domain Modeling

Define and simulate a flexible CoA structure (e.g., natural account, company code, cost center).

YAML/JSON-based metadata for easy structure replication across regions.

💾 ETL Pipelines (Simulated)

Python or SQL scripts for loading, validating, and transforming data.

Demonstrates moving data from Legacy_ERP to OneCloud target model.

Includes mapping logic (e.g., account renaming, merging accounts).

📊 Data Quality Dashboard (Optional)

Use a Jupyter Notebook or lightweight Flask dashboard to show:

Orphan records

Duplicates

Mapping mismatches

Transformation coverage

📑 Governance Layer

Excel/CSV-based rules engine or SQL-based rule enforcement.

Simulated governance process (approval flows, change logs).

📦 Integration Touchpoints

Mock data for OTC, PTP, RTR interactions.

Simulated integration showing dependencies between CoA and other finance modules.

🧰 Tools Used

SQL (PostgreSQL or SQLite)

Python for ETL/validation

Pandas, SQLAlchemy

Optional: Streamlit/Flask for dashboard; YAML for metadata
