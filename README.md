# bias-detection-techniques
This repository contains all the code necessary to replicate the research: Navigating Bias: A Comparative Analysis of Bias Detection Techniques in Machine Learning Algorithms (Kuchalskytė, 2025), which is a study on bias detection in machine learning. The files are structured to ensure clarity in execution, enabling researchers to reproduce the study or apply the techniques to new datasets. Below is an outline of the key components and the recommended execution order.

## Repository Structure 
### 1. Thesis Folder
This folder includes all the code necessary to replicate the research conducted within my master thesis (Navigating Bias: A Comparative Analysis of Bias Detection Techniques in Machine Learning Algorithms). It includes the following workbooks:

#### 1.1 Society Simulation Workbook
* Generates 8080 synthetic societies varying in bias (10 levels), scaricty (2 levels) and linearity (2 levels).
* Defines the relationships between variables and introduces bias systematically.
* This should be run first to create the dataset used in subsequent analyses.

#### 1.2 Bias Detection Workbooks (Thesis-Specific)
* Each bias detection technique used in my thesis (Navigating Bias: A Comparative Analysis of Bias Detection Techniques in Machine Learning Algorithms) has a dedicated notebook.
* These workbooks include both the technique implementation and the evaluation (correlation analysis) applied to the simulated societies.
* The correlation analysis computes correlations between bias coefficients and detection results and is used to quantify each technique's effectiveness.
* Run these after generating the simulated societies from the previous workbook.

### 2. Generalised Folder
* Provide reusable versions of each technique, adaptable for new datasets.
* These scripts allow independent application.

### 3. Example Folder
Includes the code needed to exemplify the use of the techniques on an example data set from R. First run the code of each technique from the `Generalised Folder` before running the code of the example usage.
* Demonstrates how the generalized bias detection techniques can be applied to real-world data.
* Helps validate the techniques beyond synthetic simulations.

## How to Run the Code
* If you want to replicate the thesis (Navigating Bias: A Comparative Analysis of Bias Detection Techniques in Machine Learning Algorithms) results, run the code from the `Thesis Folder`. More specifically:
    - Start with the Society Simulation Workbook to generate data.
    - Select and run the relevant Bias Detection Workbook.
* If you want to utilise the techniques for personal bias assessment, make use of the code in the `Generalised Folder`.
* If you want to see how the technques work on the example data:
    - Run the code of each technique in the `Generalised Folder`.
    - Run the code in the `Example Folder`.
