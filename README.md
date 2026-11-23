# Statistical Analysis in R

A collection of coursework-based statistical analyses in R, covering programming fundamentals, exploratory data analysis, correlation and regression, and statistical inference with biological and environmental datasets.

## Contents

| File | Focus |
| --- | --- |
| `analysis/workshop-01-r-fundamentals.Rmd` | R data structures, basic programming, matrices, data import, and visualizations using penguin data. |
| `analysis/workshop-02-descriptive-statistics.Rmd` | Descriptive statistics, variability, distributions, and exploration of BMI data. |
| `analysis/workshop-03-correlation-regression.Rmd` | Covariance, Pearson and Spearman correlation, regression, and environmental/agricultural datasets. |
| `analysis/exam-01-statistical-analysis.Rmd` | Statistical analyses of coral, owl, and road accident datasets, including regression and hypothesis testing. |

## Data

The `data/` directory contains the original datasets provided with the coursework: `Pinguinos.xlsx`, `bmi.csv`, `new_palmer_pe.csv`, `agro.csv`, `df_corales_parcial.csv`, `df_buhos_parcial.csv`, and `accidents.csv`.

## How to run

1. Download or clone this repository.
2. Open an `.Rmd` file from the `analysis/` directory in RStudio.
3. Install any packages used by that document (check its `library(...)` calls).
4. Knit the document with the working directory set to the document directory (`analysis/`). The data paths use `../data/`.

The source analyses are retained as coursework; only the data-file paths have been adapted for the repository structure. **The analyses have not been executed or independently validated as part of this packaging step.** Some documents may require additional package setup or debugging.

## Authorship

R code and analyses: Juanita Guerrero. These materials originated as academic coursework. Any names appearing on original course submissions reflect the submission format and are not a claim about code contributions.
