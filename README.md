# Video Game Sales Analysis - Data Preprocessing Project

## Introduction

This project involves data preprocessing for video game sales analysis. The raw data is cleaned and prepared for analysis through various data imputation techniques including:

- Data Cleaning
- Encoding
- Discretization/Binning
- Outlier Detection and Treatment
- Normalization
- Data Visualization

## Dataset

The dataset contains information about various video games and their sales, ratings, and other attributes. Below is a brief description of the dataset:

| Name                         | Platform | Year_of_Release | Genre        | Publisher | Global_Sales | Critic_Score | User_Score | Developer | Rating |
|------------------------------|----------|-----------------|--------------|-----------|--------------|--------------|------------|-----------|--------|
| Wii Sports                   | Wii      | 2006            | Sports       | Nintendo  | 82.53        | 76           | 8          | Nintendo  | E      |
| Super Mario Bros.            | NES      | 1985            | Platform     | Nintendo  | 40.24        |              |            |           |        |
| Mario Kart Wii               | Wii      | 2008            | Racing       | Nintendo  | 35.52        | 82           | 8.3        | Nintendo  | E      |


## Data Preprocessing Steps

### 1. Data Import
We imported the dataset using `pd.read_csv()` and used `df.head()` and `df.tail()` to print the initial and final values of the dataset.

### 2. Initial Data Visualization
Histograms and heatmaps were created to visualize the dataset before any modifications. This helps in comparing the changes post-processing.

### 3. Data Type Correction
We checked the data types of all the columns and found that the `Year_of_Release` was in float type. We corrected it to integer type.

### 4. Encoding
Categorical variables were encoded to numerical values to make them suitable for analysis.

### 5. Discretization/Binning
Continuous variables were discretized into bins to simplify the analysis and improve interpretability.

### 6. Outlier Detection and Treatment
Outliers in the dataset were detected and treated to avoid skewing the analysis results.

### 7. Normalization
Data normalization was performed to scale the numerical values to a common range without distorting differences in the ranges of values.

### 8. Data Visualization
Post-processing, various data visualization techniques were applied to understand the trends and patterns in the data.

## Conclusion
The preprocessing steps outlined above help in cleaning and preparing the dataset for further analysis. The cleaned dataset can be used for various machine learning tasks to predict trends and patterns in video game sales.
