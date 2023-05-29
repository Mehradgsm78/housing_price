housing_price
==============================

The objective of this project is to use Kaggle's Housing Prices - Advance Regression Techniques data set and train two models, a linear model and the
(approximately) best possible model (using any learner). To find the best model, we will need to do model selection (e.g. fit
multiple models and try different selection hyperparameters).

Then we will focus on explain the models and Interpretability of each of them.

For Linear model:
We use the coefficients to explain the linear model.

For Non-linear model:
We use the following three model-agnostic methods to explain your model.

1. Individual conditional expectation (ICE) plot
2. Feature importance; Either permutation feature importance (a model agnostic method) decision tree or feature importance (a
model specific method).
3. Shapley values

The documentation and the figures can be found in the reports folder. 

As an example, look at the figure below which is showing the features values using SHAP value. 

<img width="554" alt="Screen Shot 2022-12-06 at 11 15 54 AM" src="https://github.com/Mehradgsm78/housing_price/assets/132492356/36d0a6ee-ac00-469b-8ae9-9239b9033707">


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
