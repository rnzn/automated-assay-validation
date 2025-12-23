# automated-assay-validation
R scripts for validation of bioanalytical assays.
# Automated Assay Validation Workflow in R

## Project Overview
In high-throughput screening and clinical diagnostics, manual analysis of assay performance is prone to human error and variability. This project establishes a standardized R-based workflow to validate bioanalytical assays according to ICH Q2(R1) guidelines.

## Key Features (In Development)
* **Linearity Assessment:** Automated regression analysis ($R^2$, residual plots) to define the dynamic range.
* **LOD/LOQ Calculation:** Statistical determination of Limit of Detection and Quantitation using the $3.3\sigma/S$ and $10\sigma/S$ method.
* **Robustness Testing:** 2-Way ANOVA implementation to detect batch effects and temperature deviations.
* **Visualization:** Automated generation of publication-ready standard curves using `ggplot2`.

## Technologies
* **Language:** R (v4.x)
* **Libraries:** `ggplot2`, `dplyr`, `tidyr`, `stats`
