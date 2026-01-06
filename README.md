# CTN-0094 Demographics Analysis

This repository section contains my Final Project for graduate-level Statistical Computing / Biostatistics coursework. 

This project analyzes demographic characteristics of participants enrolled in opioid use disorder (OUD) treatment studies using publicly available data from the public.ctn0094data R package. The analysis focuses on describing and comparing participant demographics across three large Clinical Trials Network (CTN) studies (CTN-0027, CTN-0030, and CTN-0051).
The workflow was implemented in R using Quarto and structured as a reproducible academic-style report. An analysis dataset was created by restricting the sample to participants with a valid first randomization record and excluding individuals with missing age or key categorical demographic variables. Variable labels were applied for clarity, and CTN project identifiers were harmonized to enable cross-study comparison.
Exploratory analyses include multi-panel histograms, boxplots, violin plots, and faceted visualizations to examine age and demographic distributions across CTN projects. A formatted summary table was produced using gtsummary to describe the study population by project. Formal statistical testing was conducted to assess whether observed differences across studies were statistically and clinically meaningful, with results incorporated into the narrative using inline reporting.
This project highlights reproducible data preprocessing, cross-study harmonization, clear demographic reporting, and transparent statistical communication, reflecting analytical workflows commonly used in clinical trials and population health research.

Tools & Methods
R, Quarto
tidyverse (dplyr, ggplot2)
public.ctn0094data, gtsummary
Reproducible reporting with inline statistics

    CTN-0094 report (clinical trial / demographics + modeling + visualization)

What this demonstrates

    Reports render cleanly with no errors/warnings and no stray/unformatted output
    Code follows tidyverse style and is formatted consistently
    Key results (counts, p-values, etc.) are inserted using inline R code (no hard-coded values)
    Figures are publication-ready with clear who/when/what labels and at least one faceted plot (CTN)
    Methods sections document R version and package versions
    Uses tables appropriate for reporting (e.g., gtsummary demographics table for CTN)

Files

    ctn_report.qmd → rendered output: ctn_report.html

Notes
This project is shared as a portfolio example of reproducible reporting, applied statistical computing, and public-health oriented data analysis in R/Quarto.
