glucose Study Data Analysis
This repository contains an  analysis of glucose  dataset .The analysis aims to preprocessing on data for further analysis.


Methodology

The analysis includes:
Data cleaning and preprocessing:
-Identify the count of observations and the features recorded in the glucose dataset.
-Validate if the data types match expectations for each feature if not changing the type.
-Assess which columns contain valuable information.
-Identify columns with negligible value and articulate reasons for their exclusion from further analysis.
-Investigate the presence of duplicate records and determine potential reasons for duplication.
-Inspect differences between calibration measures and sensor data (difference and frequency of measurements)
-Calculate the percentage of missing data for each feature.
-Explore possibilities for imputing missing data.
-Check for any time gaps in the dataset that may affect the temporal continuity.

Visual Exploration:
-Plot glucose levels over time to visually identify trends, patterns, and cycles.
-Look for abnormalities identify those records by quantile(getting outliers) and winsorizing to transform data

Decision for Quality Enhancement:
-Decide what to do with records that have large differences in sensor and calibration measurement.
-Remove duplicate records, ensuring data integrity and avoiding redundancy.
-Employ suitable imputation methods for handling missing data, balancing accuracy and robustness.
-Exclude columns with minimal or none value to streamline the dataset and improve focus on relevant information.
-finding any time gaps in the dataset and develop a strategy how to handle the gaps by mean and forward fill method.
-Develop a strategy for managing abnormal glucose readings and transforming for  investigate further.

files:
glucose.ipynb: Jupyter Notebook containing the complete analysis workflow
config.yaml: Configuration file with glucose file path  
glucose.csv  


How to Use
Clone the repository.
Execute glucose.ipynb in a Jupyter Notebook environment.

Author
F. Monfared f.monfared@st.hanze.nl