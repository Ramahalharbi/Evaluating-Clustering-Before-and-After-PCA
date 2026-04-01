# Evaluating Clustering Performance: Before and After PCA

## Project Description
This project investigates the impact of dimensionality reduction on clustering performance[cite: 3]. [cite_start]By comparing results from a high-dimensional dataset against a version transformed by Principal Component Analysis (PCA), the study evaluates how reducing features affects cluster cohesion and visual interpretability[cite: 

## Objectives
**Assess Dimensionality Impact:** Understand how reducing the number of features influences the K-Means algorithm
**Visual Comparison:** Determine if a 2D projection provides a clearer representation of data clusters
**Information Trade-off:** Analyze whether critical data patterns are lost during the PCA transformation

## Technical Methodology

### 1. Data Preprocessing
* **Standardization:** All numerical features are scaled using standardization, which is a requirement for both K-Means and PCA to ensure feature parity[cite: 

### 2. Clustering Baseline
**Original Data Clustering:** K-Means is first applied to the full-dimensional original dataset[cite: 20].
**Metric Recording:** Results are recorded to serve as a baseline for comparison[cite: 21].

### 3. Dimensionality Reduction (PCA)
**Transformation:** The dataset is reduced specifically to 2 principal components.
**Transformed Clustering:** K-Means is reapplied to the transformed 

### 4. Visualization & Analysis
** Clusters are visualized using the PCA components to compare cluster separation visually.
**Critical Evaluation:** The project concludes with an analysis of which approach is superior based on the clarity of clusters and the retention of important information.
