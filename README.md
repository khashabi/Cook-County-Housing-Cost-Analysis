# Cook County Housing Cost Analysis

This project analyzes housing cost data from **Cook County, Illinois** with the goal of understanding the factors that influence residential property values and building a predictive model for housing prices.

Using publicly available assessment data, the project walks through:
- Exploratory data analysis (EDA) to understand distributions, relationships, and data quality
- Feature selection and preprocessing
- Linear regression modeling to predict housing values
- Model evaluation and interpretation

The analysis is organized into a sequence of Jupyter notebooks that document the full workflow from raw data to model results.




---

## Notebooks Overview

### `part1-eda.ipynb` — Exploratory Data Analysis
This notebook focuses on understanding the dataset and preparing it for modeling. It includes:
- Loading the Cook County housing dataset
- Inspecting data types, missing values, and basic summary statistics
- Visualizing distributions of key variables
- Exploring relationships between features and housing value
- Identifying potential transformations or cleaning steps needed before modeling

The goal of this notebook is to build intuition about the data and inform modeling decisions.

---

### `part2-model.ipynb` — Housing Price Modeling
This notebook builds on the cleaned data from the EDA phase and focuses on prediction. It includes:
- Feature selection and preprocessing
- Train/test splitting
- Building a linear regression model to predict housing value
- Evaluating model performance using error metrics
- Interpreting model results and discussing limitations

This notebook demonstrates a complete, end-to-end modeling workflow using standard data science practices.

---

## Data Download Instructions

The raw dataset is not stored directly in this repository due to file size constraints.  
Instead, the data and accompanying documentation are provided as a **ZIP file** hosted on Google Drive.

### Download the Data
Download the ZIP file here:  
[cook_county_data.zip](https://drive.google.com/file/d/1JAb7lAd7uUs0V_kZObzTF2zmuQj5Jrev/view?usp=sharing)

The ZIP file contains:
- The CSV dataset used in the analysis
- A codebook describing the variables in the dataset

### How to Use the Data
1. Download and unzip the file.
2. Place the CSV file into a local directory
3. Update the file path in the notebooks if necessary.
4. Run the notebooks from top to bottom.

---

## Requirements

To run the notebooks locally, you will need Python and the following libraries:

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- jupyter  

You can install them with:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook



