sle-proteomics-biomarker-discovery/
│
├── data/
│   ├── synthetic_proteomics_matrix.csv
│   ├── synthetic_clinical_metadata.csv
│   └── README.md
│
├── notebooks/
│   └── 01_proteomics_biomarker_analysis.ipynb
│
├── results/
│   ├── differential_expression_SLE_vs_control.csv
│   ├── biomarker_auc_ranking.csv
│   ├── biomarker_activity_correlations.csv
│   ├── analysis_summary.json
│   └── figures/
│       ├── 01_volcano_plot.png
│       ├── 02_candidate_biomarker_heatmap.png
│       ├── 03_candidate_boxplots.png
│       └── 04_roc_curves.png
│
├── src/
│   ├── analysis.py
│   ├── visualization.py
│   └── run_analysis.py
