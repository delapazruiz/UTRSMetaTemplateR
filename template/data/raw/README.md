# Raw Data Directory

## 🛑 Critical Rule: Immutable Data
Data in this folder must **never** be edited, renamed, or deleted. Any data cleaning or transformation must be performed via scripts located in the `/scripts` directory, with results saved to `/data/processed`.

---

## FAIR Metadata

### 1. Findability & Provenance
*   **Origin:** [Insert Source Name, e.g., CBS, KNMI, or Lab Experiment]
*   **Date Accessed:** YYYY-MM-DD
*   **Persistent Identifier (DOI/URL):** [Link to original data source]
*   **License:** [e.g., CC-BY-4.0]

### 2. Accessibility
If the data is too large for GitHub ( >50MB) or contains sensitive information:
*   **Location:** [e.g., "Stored on University Secure Drive" or "Available on Zenodo"]
*   **Access Protocol:** [e.g., "Request access via Principal Investigator"]

### 3. Interoperability & Reusability (Data Dictionary)

| File Name | Format | Description | Variables/Columns |
| :--- | :--- | :--- | :--- |
| `raw_survey_v1.csv` | CSV | Initial respondent data | `id`, `age`, `score` |
| `sensor_logs.json` | JSON | Machine output logs | Timestamp, Voltage |

---

## File Integrity
To ensure reproducibility, the MD5 checksums for the raw files are:
*   `raw_survey_v1.csv`: `[insert hash here]`

---
*This directory structure follows the FAIR4RS guidelines for Open Science in the Netherlands.*
