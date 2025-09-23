# Seeing Through the Borderline Lens

This repository contains the code, data, and supplementary materials for the preprint:

**Marinho, A. S., Chagas, C., Galduroz, J. C., Figueiredo, T., de Oliveira Martins Sassi, F. C., Junio, E. S., … de Mello, C. B. (2025, September 15). _Seeing through the borderline lens: how family perceptions and attributional bias shape borderline personality disorder_. PsyArXiv. [https://doi.org/10.31234/osf.io/hzjex_v2](https://doi.org/10.31234/osf.io/hzjex_v2)**

---

## Abstract

Borderline Personality Disorder (BPD) is marked by emotional dysregulation and interpersonal instability, with family environment recognized as a key etiological factor. This study systematically compares patient-family dyads using genogram analysis and attributional bias assessment. Six female patients with BPD and six family members participated. Data included a BPD symptom measure, an attributional bias task, and semi-structured interviews for genogram construction exploring family emotional relationships and risk behaviors (ERRB). Key findings: patients showed higher intentionality scores and more reports of physical abuse, whereas family members reported more distant/poor relationships. Personalization bias predicted continuous symptom severity. These findings highlight how attributional biases and ERRB shape BPD symptoms and suggest integrating family narratives with cognitive assessments enriches clinical understanding.

---

## Repository Structure

seeing-through-borderline-lens/
│
├── README.md # Project description and instructions
├── LICENSE # CC-BY 4.0 License
├── data/ # Data files (e.g., CSV, XLSX)
│ └── errb_data.csv
├── scripts/ # R scripts and R Markdown files
│ ├── analysis.R
│ └── analysis.Rmd
├── results/ # Figures, tables, and generated reports
│ └── figures/
│ └── tables/
└── supplementary/ # Additional materials
└── seeing-through-borderline-lens.docx


---

## How to Use

1. Clone the repository:
```bash
git clone https://github.com/your-username/seeing-through-borderline-lens.git
```
2. Open scripts/analysis.Rmd in RStudio.

3. Install required packages (if not already installed):
```
install.packages(c("tidyverse", "knitr", "ggplot2", "readr"))
```
4. Knit the R Markdown file to HTML or PDF to reproduce the analyses and figures.

5. Generated results (figures, tables) will appear in the results/ folder.

## Data

The data/ folder contains anonymized and processed datasets used in the study. For raw materials and additional supplementary files, see our OSF project
.

[**Click here to see the Sankey diagram data**](https://marinhocarolina.github.io/seeing-through-borderline-lens/data)

## License

This project is licensed under the CC-BY 4.0 International License, consistent with the preprint license.

## Citation

If you use this repository or the data/code for research, please cite:

Marinho, A. S., Chagas, C., Galduroz, J. C., Figueiredo, T., de Oliveira Martins Sassi, F. C., Junio, E. S., … de Mello, C. B. (2025, September 15). Seeing through the borderline lens: how family perceptions and attributional bias shape borderline personality disorder. PsyArXiv. https://doi.org/10.31234/osf.io/hzjex_v2

## Interactive Visualization

[**Click here to see the interactive Sankey Diagram!**](https://marinhocarolina.github.io/seeing-through-borderline-lens/SeeingTBorderlineLens.html)

This visualization was created with R and the networkD3 library.
