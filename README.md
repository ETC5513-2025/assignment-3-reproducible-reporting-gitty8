# ETC5513 Assignment 3
## International Education Cost vs QS University Rankings Analysis

**Project Overview**
This research project analyzes the relationship between study costs and university quality rankings to help international students make informed decisions about their study destinations. We compare total education costs against QS World University Rankings to identify cost-effective options for Master's degree programs.
🎯 Research Questions

Do top QS rankings (higher academic quality) equal higher costs?
Which countries offer the best value for international students?
How can students find cost-effective study options without compromising quality?

**Dataset Description**
####Data Sources

1. QS World University Rankings 2024-2025

- Source: Kaggle - World's Best Universities QS Rankings 2025
- Contains: Academic reputation, graduate employability, sustainability metrics
- Purpose: Global benchmark for university comparison


2. International Education Cost Dataset

- Source: Kaggle - Cost of International Education
- Contains: Comprehensive cost breakdown by country
- Includes: Tuition + Living + Visa + Insurance costs



**Scope**

- Academic Level: Master's degree programs only
- Geographic Coverage: Top 10 countries with highest QS rankings
- Time Frame: 2024-2025 academic year

**Methodology**
Our analysis follows a systematic 5-step process:

1. Data Integration: Merge QS Rankings 2024 & 2025 data
2. Country Selection: Identify top 10 countries from QS rankings
3. Data Filtering: Filter cost dataset for selected countries
4. Program Focus: Select Master's level programs only
5. Cost Calculation: Calculate total study cost (Tuition + Rent + Visa + Insurance)

📁 Project Structure
project/
├── data/
│   ├── raw/
│   │   ├── qs_rankings_2024.csv
│   │   ├── qs_rankings_2025.csv
│   │   └── international_education_costs.csv
│   └── processed/
│       └── merged_data.csv
├── analysis/
│   ├── data_processing.qmd
│   ├── visualization.qmd
│   └── statistical_analysis.qmd
├── presentation/
│   ├── slides.qmd
│   └── presenter_notes.md
├── results/
│   ├── figures/
│   └── tables/
└── README.md

**Tools & Technologies**

- Analysis: R, Quarto
- Visualization: ggplot2, DiagrammeR/Mermaid
- Presentation: Quarto Revealjs
- Data Processing: dplyr, tidyr

**How to Run This Analysis**

####Prerequisites
r
*Required R packages*
install.packages(c("tidyverse", "readr", "ggplot2", "DiagrammeR", "quarto"))

####Steps

1. Clone this repository
2. Download datasets from Kaggle links provided above
3. Place raw data files in data/raw/ folder
4. Run analysis scripts in order:

- analysis/data_processing.qmd
- analysis/visualization.qmd
- analysis/statistical_analysis.qmd

5. Generate presentation: quarto render presentation/slides.qmd

**Key Findings**
[This section will be filled after completing the analysis]

Finding 1: [To be added]
Finding 2: [To be added]
Finding 3: [To be added]

**Group Members**

[Your Name]: Data collection, methodology design, problem analysis
[Team Member 2]: Data analysis, statistical modeling
[Team Member 3]: Visualization, results interpretation

**References**

1. QS World University Rankings. (2024-2025). Retrieved from Kaggle.
2. International Education Cost Dataset. Retrieved from Kaggle.


**License**
This project is for educational purposes. Data sources have their own licensing terms - please refer to original Kaggle datasets for usage rights.

Last Updated: Jun 01 2025
Status: Completed