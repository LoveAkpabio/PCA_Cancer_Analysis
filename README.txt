# PCA Cancer Analysis

## Description
In this project, we conduct PCA on a cancer dataset, which is downloaded from `sklearn.datasets’. To some extent, the goal is to find the most important variables that would facilitate acquisition of the funding from the donors to the Anderson Cancer Center by limiting them again to p=2.

## Installation
However, to run this project you have to configure your environment with these libraries: Make sure you have Python installed, along with the following packages:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`

You can install the required libraries using pip:

```bash
pip install pandas, numpy, matplotlib, seaborn, scikit-learn


##Usage
Launch the Jupyter Notebook and go to the project directory.
Now execute the cells in the notebook throughout in order to proceed with the rest of task.
The notebook has the code snippets for applying PCA, visualization and applying logistic regression (if opted by the user).
Data
To perform this analysis, this study employed a breast cancer dataset from sklearn.datasets, a python library for various datasets. It contains descriptors for quantitative characteristics measures extracted from tumors of breast cancer patients.

##Key Features
Feature Count: 30
Target: Malignant or benign tumour/Finding of any type of cancer

##Results
The analysis performs the following:

PCA Implementation: Limits the data down to only, or close to, two dimensions.
Visualizations:
Explained variance ratio
PCA component plot
The results of logistic regression if implemented

Interpretation of Results
Mean of the explained variance ratio gives the percentage of variation explained by each of the principal component.
In this respect, the PCA component plot shows the position of the particular data points in relation to the two first principal components and pattern clusters can be easily detected.
Logistic regression, if done, offers understanding of the usefulness of the approach for reducing dataset and diagnosing cancer.
Conclusion
As it was shown in the PCA analysis, the dimensionality of the cancer dataset is significantly reduced, although the most important characteristics are preserved. This approach may help Anderson Cancer Center in the identification specific features that affect funding.

Author
Love Akpabio