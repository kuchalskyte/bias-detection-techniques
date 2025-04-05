# Thesis Study - Code Documentation

This folder contains all the code necessary to replicate the analysis conducted in my thesis study (Navigating Bias: A Comparative Analysis of Bias Detection Techniques in Machine Learning Algorithms). The workflow consists of two main parts: the Simulation Study, which generates the synthetic societies, and the Technique Workbooks, which apply different bias detection techniques to the simulated data.

## 1. Simulation Study
* This workbook contains all the code required to generate the societies analyzed in the thesis (Navigating Bias: A Comparative Analysis of Bias Detection Techniques in Machine Learning Algorithms).
* It must be run first before executing any of the technique workbooks.
* Running this workbook will generate the necessary datasets that the subsequent workbooks depend on.

## 2. Technique Workbooks
Each technique is implemented in a separate workbook. These workbooks rely on the datasets produced by the Simulation Study and should only be run after the Simulation Study workbook has been executed.

### 2.1 Technique A - Wasserstein Analysis
* This workbook contains the code necessary to perform Wasserstein Analysis.
* It includes analyses of positive and negative error distributions across different demographic groups.

### 2.2 Technique B - AUC Analysis
* This workbook contains the code necessary to compute AUC (Area Under the Curve) Analysis.
* The analysis is structured into three different scenarios:
   - Scenario 1
   - Scenario 2A
   - Scenario 2B

### 2.3 Technique C - Error Variance Analysis
* This workbook contains the code necessary to perform Error Variance Analysis
