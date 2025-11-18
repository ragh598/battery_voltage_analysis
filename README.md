# Battery Voltage Analysis

Exploratory data analysis and regression modeling for battery voltage prediction.
The data collected from a motor test to better understand the behavior when the drone operates at disturbed environments. 
This repository contains a complete analytical pipeline from data preprocessing through model evaluation.

These experiment were conducted on Tyto Motor Test bench

![quadrotor](https://github.com/user-attachments/assets/52b99389-4be0-42d8-bcbc-9c715869472f)


## Overview

This project investigates battery voltage behavior through statistical analysis and predictive modeling. The analysis employs both linear and polynomial regression approaches to model voltage characteristics and compare their predictive performance.

## Methodology

The analysis follows a structured pipeline:

1. Data loading and preprocessing
2. Exploratory data analysis with statistical summaries
3. Data integration across multiple test files
4. Visualization of voltage distributions and correlations
5. Linear regression baseline modeling
6. Polynomial regression for non-linear relationships
7. Comparative evaluation using R², RMSE, and MAE metrics
8. Results export and documentation

## Dependencies

- Python 3.7+
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- scipy

Install dependencies via:
```bash
pip install -r requirements.txt
```

## Usage

Clone the repository and launch the Jupyter notebook:

```bash
git clone https://github.com/yourusername/battery-voltage-analysis.git
cd battery-voltage-analysis
jupyter notebook Complete_Analysis_of_Battery-Voltage.ipynb
```

Execute cells sequentially to reproduce the analysis.

## Project Structure

```
battery-voltage-analysis/
├── Complete_Analysis_of_Battery-Voltage.ipynb
├── StepsTest_19pV_1920.csv
├── StepsTest_19V_1920.csv
├── StepsTest_20pV_1900.csv
├── StepsTest_20V_1900.csv
├── README.md
└── requirements.txt
```

## Results

The analysis provides:
- Statistical characterization of voltage distributions
- Correlation analysis between variables
- Comparative performance metrics for regression models
- Comprehensive visualizations of model predictions vs actual values

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss proposed modifications.

## Contact

GitHub: [@ragh598](https://github.com/ragh598)
