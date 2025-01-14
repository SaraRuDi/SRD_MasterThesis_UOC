# SRD_MasterThesis_UOC
# Diabetes Segmentation Project: Clustering Algorithms for Diabetes Data Analysis

This repository contains the code and documentation for my master's thesis project titled **"Segmentation of Diabetes Patients Using Clustering Algorithms: An Unsupervised Machine Learning Approach."** The goal of the project is to explore unsupervised learning techniques to segment diabetic and prediabetic populations, focusing on supporting targeted healthcare interventions.

## Project Overview

This project utilizes a dataset derived from the CDC's Behavioral Risk Factor Surveillance System (BRFSS), containing **253,680 entries**. The analysis investigates the relationship between health and social indicators with diabetes prevalence. Key features of the project include:

- **Data preprocessing**: Handling mixed data types (numerical and categorical) using encoding techniques, dimensionality reduction, and feature selection.
- **Clustering algorithms**: Implementation and evaluation of innovative algorithms like K-Prototypes, ROCK, and Genetic Algorithms.
- **Explainability**: Use of SHAP and LIME for interpretability, along with decision tree analysis.
- **Visualization**: Results visualized using **Plotly** for clear and interactive presentation.


## Key Features and Methodology

1. **Data Preprocessing**:
   - One-Hot Encoding for nominal variables.
   - Label Encoding for ordinal variables.
   - Dimensionality reduction with Multiple Correspondence Analysis (MCA).

2. **Clustering Algorithms**:
   - **K-Prototypes**: For clustering mixed categorical and numerical data.
   - **ROCK**: A density-based algorithm designed for categorical data.
   - **Genetic Algorithm-based Clustering**: Custom implementation for optimization of cluster assignments.

3. **Interpretability**:
   - Use of **SHAP** and **LIME** for explainable clustering results.
   - Decision tree analysis for cluster interpretation.

4. **Evaluation**:
   - Stability analysis to identify robust parameter configurations.
   - Visualization of clusters and interpretability metrics.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-clustering.git

2. Navigate to the project directory:
   ```bash
   cd diabetes-clustering

3. Install dependencies

4. Run Jupyter notebook
