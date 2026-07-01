# Analysis of Student Learning Trajectories using Learning Analytics and Large Language Models

This repository contains the reproducibility materials associated with the Master's Thesis:

**Analysis of Student Learning Trajectories using Learning Analytics and Large Language Models**

The repository includes the final analysis notebook, selected output tables, figures and LLM-derived feature files used to support the results reported in the thesis.

## Repository structure

```text
tfm-learning-analytics-llm/
├── notebooks/
│   ├── Student_Learning_Trajectories_LA_LLM_FINAL.ipynb
│   └── Student_Learning_Trajectories_LA_LLM_FINAL.html
├── outputs/
│   ├── figures/
│   ├── tables/
│   └── llm_features/
├── data/
│   └── README.md
├── requirements.txt
└── README.md
```

## Contents

- `notebooks/`: final analysis notebook in `.ipynb` and `.html` format.
- `outputs/figures/`: figures generated during the analysis and used to support the thesis results.
- `outputs/tables/`: result tables generated during the analysis and used to support the thesis results.
- `outputs/llm_features/`: files containing the semantic features extracted from selected code submissions using LLM prompts.
- `data/`: data access note. The original dataset is not redistributed in this repository.
- `requirements.txt`: list of Python packages needed to run the notebook.

## Data availability

The original data files are not included in this repository. The analysis is based on the CSEDM Data Challenge 2021 dataset described in the thesis and in the `data/README.md` file.

To reproduce the analysis, the original dataset files should be obtained from the source indicated in `data/README.md` and placed in the `data/` folder using the expected file names.

The repository does not redistribute the original CSV files in order to avoid sharing the source educational data directly. Instead, it documents the expected data structure and the analytical workflow used to process the dataset.

## Reproducibility note

The notebook is provided to document the full analytical workflow and support transparency of the results reported in the thesis. Some paths may need to be adapted depending on the local environment before re-running the analysis.

The repository includes selected generated outputs, including tables, figures and LLM-derived feature files. These materials are included to make the analysis easier to inspect and to support reproducibility of the results presented in the thesis.

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
