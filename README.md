# Lecture 04: Statistical Modeling

Course notes for ECON/NUC_ENG-5360, covering explorative data analysis (EDA), statistical modeling with linear and logistic regression.

## Contents

- [`Lecture04_Statistical_Modeling_10_15.ipynb`](./Lecture04_Statistical_Modeling_10_15.ipynb) — lecture notebook with a Pandas recap, linear regression with `statsmodels`, model interpretation and evaluation, and logistic regression using the Pima diabetes data. The appendix also includes examples of multiclass classification, gradient descent, polynomial regression, and regularized models.
- [`diabetes.csv`](./diabetes.csv) — Pima diabetes dataset used in the logistic regression example. It includes predictor columns such as `Pregnancies`, `Glucose`, and `BMI`, with `Outcome` as the binary target.
- [`pima.zip`](./pima.zip) — compressed copy of `diabetes.csv`.
- [`reqiurements.txt`](./reqiurements.txt) — the dependency list currently included with these notes (`statsmodels`, `numpy`, `pandas`, and `seaborn`).

## Setup

Use Python 3 with Jupyter Notebook or JupyterLab. Install the packages used by the notebook:

```bash
python -m pip install numpy pandas seaborn statsmodels matplotlib plotly scikit-learn scipy
```

The existing `reqiurements.txt` does not list every package imported in the notebook; the command above includes those additional packages.

## Run the notebook

From this directory, launch Jupyter and open `Lecture04_Statistical_Modeling_10_15.ipynb`:

```bash
jupyter notebook
```

Run the cells in order. The notebook reads `diabetes.csv` from the current directory. Its optional appendix also contains an example that refers to a separate `References/` data file, which is not included here.
