# BioDisco Supplementary Materials

This repository contains all supplementary data, code, and figures required to reproduce the results presented in the “BioDisco” paper submission.

## Contents

- **BioDisco-master/**  
  Source code package for BioDisco.

- **data/data_eval/**  
  Contains all processed evaluation datasets.  
  - `CVD_raw_scores.csv` / `Immunology_raw_scores.csv`: Raw human scoring data.
  - `results_for_BT.csv`, `temporal-eval.csv`, `Truthhypo_relation_results.csv`: Automated results for quantitative evaluation.

- **data/data_raw/**  
  Raw input datasets for human and automated benchmarks, before processing.

- **evaluation/**  
  Jupyter notebooks for all key analyses and experiments:
  - `Ablation_eval.ipynb`: Analysis and results of ablation experiments.
  - `ablation_preprocess.ipynb`: Data preprocessing for ablation experiments.
  - `sim_eval.ipynb`: Code for similarity-based evaluation between hypotheses.
  - `TruthHypo_class.ipynb`: Relation classification for the TruthHypo dataset.

- **figure-pdf/**  
  Contains PDF versions of all figures shown in the main paper and supplementary appendix.

- **BioDisco_supplementary_materials.pdf**  
  Supplementary appendix with additional results, methods, and detailed case studies.

- **evaluation.pdf**  
  Supplementary evaluation workflow and statistical models for the BioDisco paper, detailing all steps, code, and analyses used to generate the evaluation tables and figures (including paired LLM comparisons, human survey analysis, and Bayesian mixed-effects modelling).

## Reproducibility

- All data, analysis code, and figure scripts are included to enable full reproduction of the paper’s results.
- For detailed methodology or usage instructions, please refer to the main paper and the supplementary appendix.

## Contact

For questions about data or code usage, please refer to the main paper for contact information.
