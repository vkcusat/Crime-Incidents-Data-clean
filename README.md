# Crime Incidents Data Analysis — Cleaning & EDA Pipeline

An end-to-end data analytics workflow designed to process, audit, clean, and analyze messy real-world crime incident datasets. This repository contains sequential pipelines that handle data engineering quality checks and extract hidden behavioral trends through statistical visualizations.

## 🚀 Project Pipeline Architecture

### Phase 1: Data Cleaning Workflow (`crime_data_cleaning.ipynb`)
This phase focuses strictly on preprocessing and data scrubbing to prepare a structured, reliable dataset optimized for analysis:
*   **Data Quality Auditing:** Inspects the raw DataFrame shapes, detects missing fields, and evaluates structural entry issues.
*   **Anomaly Remediation:** Identifies and resolves data irregularities, such as negative crime count metrics or invalid status markers, using logical standardizations.
*   **Structural Wrangling:** Normalizes inconsistent category labels, groups syntax variations using Pandas functions, and drops corrupted parameters.
*   **Type Optimization:** Standardizes structural indexing and data formats to enforce strict data integrity across features.

### Phase 2: Exploratory Data Analysis (`crime_eda.ipynb`)
This phase builds directly on the clean dataset output to discover critical trend clusters and incident patterns:
*   **Descriptive Summaries:** Evaluates central tendencies, variations, and baseline frequency matrices to profile the underlying dataset features.
*   **Categorical Frequency Tracing:** Groups incident indicators by type, location variables, and severity scores to isolate distribution spikes.
*   **Time-Series Breakdown:** Tracks chronological activity variations to locate seasonal shifts or frequency patterns.
*   **Visual Analytics Engine:** Leverages Matplotlib and Seaborn to map feature distributions, density graphs, and correlation matrix matrices.

## 💻 Technical Stack
*   **Language:** Python 3
*   **Core Libraries:** Pandas, NumPy, Matplotlib, Seaborn
*   **Environment:** Google Colab / Jupyter Notebook

## 🛠️ How to Run
1. Open the project repository files inside Google Colab or your local notebook interface.
2. Load the messy target dataset (`crime_incidents_messy.csv`) directly into the Phase 1 cleaning notebook to export the scrubbed output.
3. Pass the generated clean dataset file into the Phase 2 EDA notebook.
4. Execute the code cells sequentially to view data cleaning summaries and live visual analytical charts.
