# Real-World Crime Incident Data Analysis & Cleaning Project

An analytical data engineering pipeline focused strictly on preprocessing, auditing, and cleaning messy, real-world crime incident records. This project transforms raw, chaotic data into a structured, reliable dataset optimized for downstream analysis and reporting.

## 🚀 Applied Data Cleaning Workflow
The pipeline addresses data quality issues by executing the following data cleaning operations:

*   **Data Quality Auditing:** Inspects the raw DataFrame shape, identifies missing values, handles null constraints, and flags structural syntax anomalies.
*   **Handling Anomalies & Negative Values:** Locates invalid data entries (such as negative crime counts or invalid codes) and resolves them through logical replacements or removals.
*   **Structural Wrangling:** Harmonizes inconsistent string formats, cleans categories using Pandas grouping methods, and repairs corrupted columns.
*   **Type Casting & Normalization:** Standardizes data types across all features to guarantee strict data integrity and structured indexing.

## 💻 Tech Stack
*   **Language:** Python 3
*   **Core Libraries:** Pandas, NumPy
*   **Environment:** Google Colab / Jupyter Notebook

## 🛠️ How to Run
1. Open the `.ipynb` notebook file in Google Colab.
2. Load the messy dataset file using your local or Kaggle data path.
3. Execute the code cells sequentially to process the dataset and generate the cleaned output data frame.
