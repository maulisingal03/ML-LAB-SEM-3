Applied Machine Learning

Experiment 1 – Housing Dataset

Objective: 

To prepare the Housing dataset for machine learning by performing data inspection, data cleaning, normalization, and splitting the dataset into training, validation, and testing sets.

Dataset: 

- Dataset Name: Housing Dataset
- File Name: Housing.csv

Preprocessing Steps Performed: 

1. Data Cleaning: The process of identifying and removing errors, missing values, and duplicate data from a dataset.

The dataset was checked for:

- Missing values
- Duplicate rows

Duplicate rows were removed, if present, to improve the quality of the dataset.

2. Normalization: The process of scaling numerical data to a common range, usually 0 to 1, so that all features have a similar scale.

Min-Max Normalization was applied to the numerical columns using "MinMaxScaler" from Scikit-learn.

Normalization scales the numerical values to a common range, making the data suitable for further machine learning processing.

Dataset Splitting : The process of dividing a dataset into training, validation, and testing sets so that the model can be trained, tuned, and evaluated properly.

The prepared dataset was divided into three sets:

- Training Set: 70%
- Validation Set: 15%
- Testing Set: 15%

A random state of 42 was used to ensure reproducibility of the split.

Tools and Libraries Used : 

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

Files : 

- "Housing.csv" – Dataset used for the experiment.
- "EXPERIMENT_1_HOUSING.ipynb" – Jupyter Notebook containing the code and results.
- "README.md" – Documentation of the experiment.

Result : 

The Housing dataset was successfully cleaned and normalized. It was then divided into training, validation, and testing datasets using a 70:15:15 ratio.

Conclusion: 

The Housing dataset was successfully prepared for machine learning by performing two preprocessing techniques: Data Cleaning and Normalization. The prepared dataset was further split into training, validation, and testing sets for use in machine learning experiments.
About


No description, website, or topics provided.
Resources
Readme
Activity
Stars
0 stars
Watchers
0 watching
Forks
0 forks
Releases

No releases published
Create a new release
Packages

No packages published
Publish your first package
Contributors
1
 (1)

@maulisingal03
maulisingal03
Footer
© 2026 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Community
Docs
Contact
Manage cookies
