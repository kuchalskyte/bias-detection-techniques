# bias-detection-techniques
This repository contains all code necessary to replicate my thesis study on bias detection in machine learning. The files are structured to ensure clarity in execution, enabling researchers to reproduce the study or apply the techniques to new datasets. Below is an outline of the key components and the recommended execution order.

## Repository Structure 
### 1. Society Simulation Workbook
* Generates 8080 synthetic societies varying in bias (10 levels), scaricty (2 levels) and linearity (2 levels).
* Defines the relationships between variables and introduces bias systematically.
* This should be run first to create the dataset used in subsequent analyses.

### 2. Bias Detection Workbooks (Study-Specific)
* Each bias detection technique used in my thesis has a dedicated notebook.
* These workbooks include both the technique implementation and the evaluation (correlation analysis) applied to the simulated societies.
* The correlation analysis computes correlations between bias coefficients and detection results and is used to quantify each technique's effectiveness.
* Run these after generating the simulated societies from the previous workbook.

### 3. Generalized Bias Detection Scripts
* Provide reusable versions of each technique, adaptable for new datasets.
* These scripts do not include study-specific evaluations but allow independent application.

### 4. Example Usage on an R Dataset
* Demonstrates how the generalized bias detection techniques can be applied to real-world data.
* Helps validate the techniques beyond synthetic simulations.

## How to Run the Code
* Start with the Society Simulation Workbook to generate data.
* Select and run the relevant Bias Detection Workbook (for study replication) or use a Generalized Script (for new data).
* Optionally, test the techniques on the R dataset example for real-world application.
* This structure ensures flexibility, allowing both thesis replication and application to new datasets.
