Genetic Analysis of Osteosarcoma

Author: Cansu Gulum
Tools: R, tidyverse, broom, ggplot2

Project Overview

This project analyzes gene expression patterns in osteosarcoma samples.
The workflow includes data cleaning, metadata creation, exploratory plots, ANOVA-based statistical testing, and a volcano plot comparing Primary vs Metastasis conditions.

Raw data is not included due to size/privacy constraints, but the full analysis pipeline is reproducible with any similarly structured dataset.

Methods

Import and clean gene expression matrix

Convert data to tidy long format

Map samples to conditions

Single-gene visualization + ANOVA

Genome-wide ANOVA with FDR correction

Volcano plot highlighting significant genes

Summary of Results

Some genes show significant expression differences between Metastasis and Primary groups.

Volcano plot identifies genes with high fold-change and low FDR-adjusted p-values.
