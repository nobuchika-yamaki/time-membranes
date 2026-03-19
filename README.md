# Temporal Retention Review Package

This package reproduces the numerical analyses used in the revised manuscript on temporal retention in delay–dissipative systems.

## File
review_submission_temporal_retention.py

## How to run
1. Open Terminal
2. Move to Desktop:
   cd ~/Desktop
3. Run:
   python3 review_submission_temporal_retention.py

## Output folder
review_submission_temporal_retention_outputs

## Main output files
- parameter_table.csv
  Default parameters used in the simulations

- equation_table.csv
  Model equations and metric definitions

- validation_report.csv
  Numerical stability checks

- control_comparison_raw.csv
  Trial-level results for nonlinear delay, bounded linear delay, and no-delay conditions

- control_comparison_summary.csv
  Mean, SEM, and fractions for the control comparison

- figure1_left_panel_data.csv
  Data used for the left panel of Figure 1

- figure_scatter_data.csv
  Trial-level scatter data used for Figure 1 (right) and Figure 3

- chi_distribution_table.csv
  Trial-level χ band assignments

- chi_distribution_counts.csv
  χ band counts and fractions by condition

- figure2_distribution_data.csv
  Aggregated distribution data used for Figure 2

- chi_mi_correlation_overall.csv
  Overall χ–MI correlation

- chi_mi_correlation_by_control.csv
  χ–MI correlations for each control condition

- sigma_sweep_summary.csv
  Summary of the noise sweep

- delay_dispersion_summary.csv
  Summary of the delay-dispersion analysis

- manuscript_ready_summary_table.csv
  Key manuscript numbers extracted into a compact table

## Notes
- The script uses fixed random seeds for reproducibility.
- No manual editing is required after execution.
- All outputs are saved automatically as CSV files.
