# Global Retail Data – Luxury Market & Authentication Datasets

This repository contains clean, open-source sample files for schema validation, LLM pipeline testing, and tabular anomaly detection.

## 📂 Included Sample
* **`synthetic_luxury_auth_sample_150.csv`**: A 150-row balanced sample (50% `AUTHENTIC` / 50% `COUNTERFEIT_REPLICA`) mapping granular inspection zones, material specs, simulated weight deltas, and risk severity scores across High Horology, Luxury Handbags, Limited Sneakers, and Fine Jewelry.

## 📊 Schema Overview
* `Auth_Entry_ID`: Unique record identifier
* `Category` / `Brand` / `Model`: Product classification (Rolex, Patek Philippe, Hermès, Louis Vuitton, Dior x Jordan, Cartier)
* `Authenticity_Label`: Binary ground-truth label (`AUTHENTIC` vs. `COUNTERFEIT_REPLICA`)
* `Inspection_Zone`: Specific area evaluated (e.g., `Dial_Typography`, `Stitching_Density`, `Cyclops_Lens`)
* `Anomaly_Type`: Detailed description of the authentication marker or defect
* `Material_Spec`: Standardized material composition
* `Weight_Grams_Delta`: Simulated weight deviation in grams vs. factory baseline
* `Risk_Severity_Score`: Difficulty/severity score (1.0 – 10.0)

## 🚀 Full Production Datasets (CSV & JSON)
Need the complete 3,500+ row production dataset for model training and benchmarking?

👉 **[Download Full 3,500+ Row Dataset (CSV + JSON) on Gumroad](https://gumroad.com)**

---
*Curated by Martin Polák | Global Retail Data*
