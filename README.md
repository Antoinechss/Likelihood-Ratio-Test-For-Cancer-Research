<h1 align="center">Likelihood Ratio Test for Cancer Research</h1>

<p align="center">
  <em>
    Statistical analysis of feature relevance using the Likelihood Ratio Test applied to the Wisconsin Breast Cancer Dataset.
  </em>
</p>

---

## 1. Project Overview

This repository presents a statistical study based on the **Likelihood Ratio Test (LRT)** to identify the most relevant features for distinguishing **malignant** from **benign** tumors.

The project combines **theoretical foundations of hypothesis testing** with a **practical application** to medical data, focusing on nested model comparison and feature significance.

---

## 2. Objectives

The objectives of this work are to:

- Introduce the theoretical principles of the Likelihood Ratio Test  
- Apply LRTs to a real-world medical dataset  
- Identify tumor characteristics that significantly improve malignancy inference  
- Illustrate the connection between statistical theory and applied data analysis  

---

## 3. Methodological Approach

The analysis follows the classical Likelihood Ratio Testing framework:

1. Definition of null and alternative hypotheses  
2. Construction of reduced and full logistic regression models  
3. Computation of maximized log-likelihoods  
4. Derivation of the LRT statistic  
5. Statistical decision based on asymptotic theory (Wilks’ theorem)  

Each feature is tested by comparing a model excluding the feature (null model) to a model including it (full model).

---

## 4. Dataset

- **Dataset**: Wisconsin Breast Cancer (Diagnostic) Dataset  
- **Observations**: 569 tumor samples  
- **Labels**: Malignant / Benign  
- **Features**: 30 continuous variables describing tumor morphology and texture  

---

## 5. Exploratory Analysis

The figure below illustrates the distribution of the **texture (mean)** feature for malignant and benign tumors, highlighting a clear separation between the two classes.

<img width="414" height="251" alt="Screenshot 2025-12-12 at 08 37 45" src="https://github.com/user-attachments/assets/afc8db4a-d653-4ce6-870d-747d7bf00eac" />



This visual evidence motivates the statistical testing of texture-related features using the Likelihood Ratio Test.

---

## 6. Likelihood Ratio Test Results

The table below summarizes the Likelihood Ratio Test statistics and corresponding p-values for selected tumor features.

<img width="286" height="273" alt="Screenshot 2025-12-12 at 08 37 37" src="https://github.com/user-attachments/assets/8a88d0da-602b-4ad0-8858-52465ab1336b" />



Features with low p-values provide strong evidence against the null hypothesis and are considered statistically significant contributors to malignancy prediction.

---
