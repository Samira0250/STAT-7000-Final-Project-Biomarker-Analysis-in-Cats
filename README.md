# STAT 7000 Final Project – Biomarker Analysis in Cats
Exploring the Kidney-Brain Axis in a feline model of PEA15 loss of function
**Project:** Statistical comparison of blood and CSF biomarkers between genetically "Affected" and "Unaffected" cats.

---

## Overview

This R script performs:
- Data cleaning and preprocessing
- Normality and variance testing
- Group comparisons using **t-tests** or **Wilcoxon tests**
- Visualization via **boxplots** and **violin plots**
- Summary table generation for statistical results

Two datasets are analyzed:
- **Bloodwork**: `Cat_Kidney_Brain_Bloodwork.xlsx`
- **CSF**: `CSF.xlsx`

---

## Dependencies

The following R packages are required and auto-installed if missing:
```r
tidyverse, ggpubr, car, readxl
