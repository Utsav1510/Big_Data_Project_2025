# Big Data Analysis Project: Air Pollution & Climate Variability in Sydney

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
## Dataset

This project uses publicly available meteorological and air quality data for Sydney (2015–2025), retrieved from:

- [NSW Air Quality API](https://www.airquality.nsw.gov.au/air-quality-data-services/air-quality-api)  
- [BOM Climate Data Online (CDO)](http://www.bom.gov.au/climate/data/)  

The dataset includes pollutants (PM2.5, PM10, NO₂, CO, Ozone) and meteorological variables (temperature, humidity, wind speed/direction, wind variability).  

Due to size constraints, the full dataset is **not uploaded** here. Instead:  
- Dataset files for reference are provided in the zip file: DatasetsRetrieved.zip.
- Scripts to fetch and preprocess the full dataset are available in the repository.  

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
## Usage

1. Fork or clone the repository  
2. Open the notebooks in Jupyter Notebook or JupyterLab  
3. Run the notebooks in sequence (**PartA → PartB → PartC**) or directly use **Final_Run.ipynb** for the simplified main workflow  
4. All intermediate outputs, visualizations, and model results will be displayed in the respective files..

