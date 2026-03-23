# Week 4 Worksheet Repository: Exploratory Data Analysis

This repository is the starter repository for the week 4 exploratory data analysis activity.

## Repository Structure

- `README.md`: this file
- `requirements.txt`: Python packages for the activity
- `data/clean/store_week_clean.csv`: cleaned sample data for the activity
- `code/worksheet4_eda_student.ipynb`: notebook for you to complete
- `code/worksheet4_eda_sample_answers.ipynb`: sample answers notebook
- `output/`: save any figures or exported outputs here

## Getting Started

1. Create and activate a Python environment.
2. Install the required packages with `pip install -r requirements.txt`.
3. Open `code/worksheet4_eda_student.ipynb` in VS Code.
4. Work through the notebook and save any figures you want to keep in `output/`.
5. Update this `README.md` with what you find in the data.

## Analysis Notes

### Completed notebook
- `code/worksheet4_eda_student.ipynb` has been completed with all required steps.

### Repository structure
- `README.md`: repository overview, setup and analysis notes
- `requirements.txt`: required Python packages
- `data/clean/store_week_clean.csv`: cleaned weekly store data
- `code/worksheet4_eda_student.ipynb`: student notebook (completed)
- `code/worksheet4_eda_sample_answers.ipynb`: sample answers
- `output/`: generated figures and saved plots

### Cleaned dataset summary
- `data/clean/store_week_clean.csv` is a panel of weekly metrics by store, with columns:
  - `week`, `store_id`, `store_type`, `region`, `promotion_flag`, `total_hours`, `avg_hourly_pay`, `weekly_sales`, `staffing_model`
- It describes store staffing, pay, promotions, and sales outcomes over time.

### EDA findings
- `total_hours`, `avg_hourly_pay`, and `weekly_sales` were visualized with histograms; sales is more dispersed and slightly right-skewed.
- `store_type` composition is balanced and useful for group comparison analysis.
- Scatter plot of `total_hours` vs `weekly_sales` shows a positive relationship, supported by Pearson/Spearman correlation coefficients.
- Log-scaling `weekly_sales` made lower sales points easier to compare and clarified heteroskedasticity.
- Grouped plot by `store_type` reveals different clusters and sales patterns across store categories.

## Git Reminder

All relevant changes should be committed and pushed back to your own GitHub repository.
