# Systematic Review Repository: Spatiotemporal ML for Road Traffic Accident Prediction

This repository contains the complete data extraction, analysis scripts, and supplementary materials for the following paper:

**Sarbajit Paul Bappy & Avi Mondal.** (2026). *Spatiotemporal Patterns and Machine Learning for Road Traffic Accident Prediction in Developing Countries: A Systematic Review with Empirical Evidence from Bangladesh.* **Accident Analysis & Prevention**.

## 📂 Repository Structure
├── 60_paper_data.csv              # Master extraction data for 60 included studies
├── SLR_Codes.ipynb                # Python 3.12 notebook (generates all figures and tables)
├── SLR_Synthesis_Tables.xlsx      # Formatted tables matching manuscript tables
├── Prisma.pdf                     # PRISMA 2020 flow diagram
└── README.md                      # This file
text## 🔧 Requirements

```bash
pip install pandas numpy matplotlib scikit-learn wordcloud seaborn
🚀 How to Reproduce

Open 60_paper_data.csv to view the extracted data for all 60 studies.
Run SLR_Codes.ipynb to generate all figures and tables.
Check SLR_Synthesis_Tables.xlsx for exact numbers cited in the manuscript.

📊 Data Dictionary (60_paper_data.csv)

Algorithm category (Traditional ML, Deep Learning, Hybrid, etc.)
PROBAST overall risk of bias (Low, Unclear, High)
Spatiotemporal framework type (Combined, Temporal-only, Spatial-only)
Accuracy reported, AUC or AUROC reported
Temporal resolution
Study conducted in Bangladesh (Boolean)
World Bank income classification
PROBAST Analysis domain ratings

📄 Citation
Bappy, S. P., & Mondal, A. (2026). Spatiotemporal Patterns and Machine Learning for Road Traffic Accident Prediction in Developing Countries: A Systematic Review with Empirical Evidence from Bangladesh. Accident Analysis & Prevention.
📄 License
This repository is released under the MIT License.
🛡️ Contact
For questions, please open an issue in this repository.

Maintained by Sarbajit Paul Bappy
