# Global MDM Simulation: Chart of Accounts (CoA) Transformation

This project simulates a global Master Data Management (MDM) process to transform and migrate Chart of Accounts (CoA) data from a legacy ERP system to a standardized OneCloud structure.

## 🌍 Purpose

To demonstrate:

- ETL transformation of financial master data
- Mapping legacy account codes to new OneCloud format
- Basic data quality validation
- Governance-friendly MDM structure

## 🗃️ Data Files

- `data/legacy_erp_coa.csv`: Legacy CoA records
- `data/transformation_map.csv`: Mapping to OneCloud accounts
- `data/onecloud_coa_transformed.csv`: Final transformed dataset

## 🚀 How to Run

1. Clone the repository
2. Run the Python script:

```bash
python scripts/transform_coa.py
