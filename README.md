# automated-assay-validation
R scripts for validation of bioanalytical assays.
# Automated Assay Validation Workflow in R

## Project Overview
In high-throughput screening and clinical diagnostics, manual analysis of assay performance is prone to human error and variability. This project establishes a standardized R-based workflow to validate bioanalytical assays according to ICH Q2(R2) and ICH Q14 guidelines.

## Key Features (In Development)
* **Linearity Assessment:** Automated regression analysis ($R^2$, residual plots) to define the dynamic range.
* **LOD/LOQ Calculation:** Statistical determination of Limit of Detection and Quantitation using the $3.3\sigma/S$ and $10\sigma/S$ method.
* **Robustness & Design of Experiments (DoE):** Implementation of Fractional Factorial Designs to identify Critical Method Parameters (CMPs) like pH, Temperature, and Ionic Strength.
* **Visualization:** Automated generation of publication-ready standard curves using `ggplot2`.

## Technologies
* **Language:** R (v4.x)
* **Libraries:** `ggplot2`, `dplyr`, `tidyr`, `stats`
