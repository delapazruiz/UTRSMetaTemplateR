# Project Documentation

## 📖 Overview
This directory contains the supplementary documentation, rendered reports, and guides required to understand, run, and cite this research project. Following **FAIR principles**, this ensures the research is not just available, but **understandable**.

---

## 📂 Documentation Structure

| Component | Format | Description |
| :--- | :--- | :--- |
| **User Guide** | `.qmd` / `.md` | Step-by-step instructions for reproducing the analysis. |
| **API/Function Docs** | `.html` | Auto-generated documentation for functions in the `/R` folder. |
| **Data Dictionary** | `.csv` / `.md` | Detailed definitions of all variables used in the analysis. |
| **Manuscript/Report** | `.pdf` / `.docx` | The final research paper or technical report. |
| **SMP DMP** | `.pdf` | The Software Data Management Plans (e.g., following NWO/ERC templates). |

---

## 🚀 Viewing the Documentation
If this repository is configured with **GitHub Pages**, the rendered version of this documentation is available at:
👉 `https://<username>.github.io/<repo-name>/`

### To render locally (Quarto):
Ensure you have [Quarto](https://quarto.org) installed, then run:
```bash
quarto render docs/
