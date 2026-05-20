# Data Analysis and Visualisation - Car Value-for-Money Index

## Overview

This repository contains the code and written report for a Data Analysis and Visualisation project. The project uses a used car dataset to create a **Car Value-for-Money Index**.

The aim of the project is to compare used cars using more than just price. The index also considers mileage, car age, tax, MPG, and fuel type. The final score is used to identify cars that may offer better overall value-for-money.

## Files

`notebooks/car_price_analysis.ipynb`  
Contains the main Python analysis, including data cleaning, encoding, multivariate analysis, regression, PCA, clustering, normalisation, weighting, aggregation, and visualisation.

`notebooks/written_report.ipynb`  
Contains the written report for the project.

`data/raw/`  
Contains the original raw dataset.

`data/cleaned/`  
Contains cleaned or processed datasets created during the analysis.

`images/`  
Contains the visualisations used in the report.

`requirements.txt`  
Lists the Python libraries needed to run the project.

## Dataset

The dataset used for this project is a car prices dataset containing information such as:

- Model
- Year
- Price
- Transmission
- Mileage
- Fuel type
- Tax
- MPG
- Engine size
- Manufacturer

The dataset was used to build a composite index for comparing cars based on affordability, condition, age, and efficiency.

## Dependencies

The main Python libraries used are:

1. Pandas
2. NumPy
3. Matplotlib
4. Seaborn
5. Scikit-learn
6. SciPy
7. Statsmodels

Install the required dependencies using:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:

```bash
git clone YOUR_REPOSITORY_LINK_HERE
```

2. Navigate to the project folder:

```bash
cd DAV_CA1_XuTeckTan
```

3. Create and activate a virtual environment if needed.

4. Install the required libraries:

```bash
pip install -r requirements.txt
```

5. Open the notebooks in Jupyter or VS Code:

```text
notebooks/car_price_analysis.ipynb
notebooks/written_report.ipynb
```

6. Run `car_price_analysis.ipynb` to reproduce the analysis and generated results.

## Project Output

The final output is a **Car Value-for-Money Index**. A higher score means the car performs better based on the selected factors and weighting system.

The project also includes visualisations showing:

- Top 10 cars by value-for-money score
- Distribution of the final index
- Sub-index score distributions
- Key variables compared with the final index
- Average value index by manufacturer

## Credits

The dataset used in this project was sourced from Kaggle / Baselight.
