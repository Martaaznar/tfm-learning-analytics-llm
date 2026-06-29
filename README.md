# Analysis of Student Learning Trajectories using Learning Analytics and Large Language Models

This repository contains the reproducibility materials associated with the Master's Thesis:

**Analysis of Student Learning Trajectories using Learning Analytics and Large Language Models**

The repository includes the final analysis notebook, selected output tables and figures used to support the results reported in the thesis.

## Repository structure

```text
tfm-learning-analytics-llm/
├── notebooks/
│   ├── Student_Learning_Trajectories_LA_LLM_FINAL.ipynb
│   └── Student_Learning_Trajectories_LA_LLM_FINAL.html
├── outputs/
│   ├── figures/
│   └── tables/
├── data/
│   └── README.md
├── requirements.txt
└── README.md
````

## Contents

* `notebooks/`: final analysis notebook in `.ipynb` and `.html` format.
* `outputs/figures/`: figures generated during the analysis.
* `outputs/tables/`: result tables used to support the thesis results.
* `data/`: data access note. The original dataset is not redistributed in this repository.

## Data availability

The original data files are not included in this repository. The analysis is based on the CSEDM Data Challenge dataset described in the thesis. The notebook documents the preprocessing, feature engineering, semantic extraction and modelling workflow used in the analysis.

## Reproducibility note

The notebook is provided to document the full analytical workflow and support transparency of the results reported in the thesis. Some paths may need to be adapted depending on the local environment before re-running the analysis.

## Main workflow

The analysis includes:

1. Loading and preprocessing the original learning analytics data.
2. Building student-level Traditional Learning Analytics features.
3. Extracting structural code features from Java submissions.
4. Extracting semantic features from selected code submissions using LLM prompts.
5. Aggregating features at student level.
6. Training and evaluating regression and classification models.
7. Analysing fixed-point, temporal and final hold-out results.

## Author

Marta Aznar Vallés 
Master's Thesis, Universidad Carlos III de Madrid

