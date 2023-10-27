# README.md

# Fish Gut Metagenomic Analysis 

This repository contains code and data for analysis of fish gut microbiome using 16S rRNA gene sequencing.

## Contents

- `data/`: Raw and processed data files
- `code/`: Python and R scripts for bioinformatic analysis  
- `results/`: Output files, tables, plots and figures
- `reports/`: Manuscript drafts and presentations

## Overview

The analysis involved:

- Quality control
- Taxonomic classification 
- Diversity analysis
- Statistical comparisons
- Functional predictions
- Random forest classification
- Krona interactive charts 

Tools used include:

- FastQC and Fastp  
- QIIME2
- Phyloseq
- Vegan
- PICRUSt2
- RandomForest
- Krona

## Usage

The analysis can be reproduced by running the scripts in `code/` folder:

1. `fastp_qc.py`: Quality filtering
2. `qiime2_taxa_analysis.py`: Taxonomic classification 
3. `r_alpha_diversity.R`: Alpha diversity analysis
4. `r_beta_diversity.R`: Beta diversity analysis
5. `picrust2_predict_pathways.py`: Functional predictions
6. `random_forest_classification.py`: Sample classification with random forest
7. `krona_charts.py`: Interactive Krona charts

Raw data is in `data/` and outputs will be saved to `results/`.

## Contributors 

- John Doe
- Jane Doe

Please contact us with any questions!
