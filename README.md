# Air Quality and Meteorological Data Analysis

This repository contains the complete workflow for analyzing the impact of climate variability on urban air pollution in Sydney.  
It includes scripts for data collection, preprocessing, exploratory analysis, and predictive modeling using multiple machine learning methods.

---

## Project Structure

- **PartA_InitialDataCollection.ipynb** – Collects and prepares the initial dataset.  
- **PartB_FullDataCollection.ipynb** – Expands and finalizes the dataset with all relevant features.  
- **PartB_Analysis.ipynb** – Performs exploratory data analysis, clustering, and visualization.  
- **PartC_Modelling.ipynb** – Contains all model experiments (Linear Regression, Random Forest, XGBoost, SVR, ARIMA).  
- **Final_Pipeline.ipynb** – A simplified notebook containing only the necessary code to reproduce the main results 

**Note:** Be cautious when saving or naming intermediate CSV files (e.g., `combined.csv`, `full_relevant_features.csv`).  
Some steps may require adjusting file paths or names to ensure smooth execution.

---

# Installation

### Prerequisites
Make sure you have **Python 3.8+** installed.  
It is recommended to use a virtual environment (`venv` or `conda`) before installing dependencies.

### Install required libraries
The project uses the following Python libraries:

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- xgboost  
- statsmodels  
You can install them with:

pip install pandas numpy matplotlib seaborn scikit-learn xgboost statsmodels
