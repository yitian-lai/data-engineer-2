#### Overview
This repository presents a conceptual ETL blueprint for processing tax related data. The focus is strictly on Python notebook-layer data transformation, implemented using Python OOP concept.

Pipeline steps related to:
- source system extraction
- ingestion into landing folders/zones
- orchestration tools such as ADF, ADLS, SSMS are intentionally excluded. As in the current stage, the developer does not obtain any Azure sandbox. However, a small mocked dataset is used to demonstrate the data model and transformation logic

### Architecture Summary
The data flow follows a layered architecture:

Source Systems > Landing Folder / Zone > Landing Tables > Structured Tables > Dimensional Tables > Semantic Tables > Reporting / Analysis

### Script Execution Guide
- ETL Python-Based.ipynb: It encompasses a series of modular ETL processes spanning from the bronze layer (landing tables) through to the gold layer (semantic and view layers). Please note that Kaggle is used as a sample Databricks‑style Jupyter notebook environment for developers to draft and demonstrate the ETL scripts.
- Manual document: This document delivers a detailed breakdown of the complete ETL methodology.
