### If we introduce an animal species of specific nativeness,occurrence and seasonality to a National Park - can we predict its abundance?
Project for DATA 1030 (Fall 2020)

In this project we use an NPS database of animal and plant species from individual national parks and build a model that aims to solve a classification problem for animal species.

Written in Jupyter Notebook. Uses the following packages:
  - python=3.7
  - matplotlib=3.2.2
  - pandas=1.0.5
  - scikit-learn=0.23.1
  - numpy=1.18.5
  - pip=19.1.1=py37_0
  - pip:
    - xgboost==1.1.1
  - shap=0.35.0

These are summarized in the data1030 yml file.

Folder src: Contains Jupyter-Notebooks for code

Folder data: Contains csv files for original data from https://www.kaggle.com/nationalparkservice/park-biodiversity as well as detailed calculations for the baseline f1-score with weighted average.

Folder figures: Contains figures generated by code for EDA, ML algorithms and feature importance analysis

Folder report: Contains PDF of detailed report of entire project

Folder results: Contains pickle file for the fitted model that gives the best score
