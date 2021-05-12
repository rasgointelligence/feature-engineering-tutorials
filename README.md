# Tutorials: Feature Engineering in Python

This repository contains tutorials and code to enable data scientists to easily create new features and evaluate their importance for supervised machine learning. 

At Rasgo, we're data scientists, and we're really interested in the problem of feature engineering and everything that leads to that. We wrestle with these types of problems all the time and thought we'd capture examples of recipes for how to use some of the best tools available in this space. We're also working on our own SDK for feature engineering and want to provide a place to showcase new features as they are ready for testing. We hope you find this repo useful. Please let us know if there are other examples you'd like to see us include either by filing issues or pinging us on our Slack.

Please join us on the [Rasgo User Group Slack](https://join.slack.com/t/rasgousergroup/shared_invite/zt-nytkq6np-ANEJvbUSbT2Gkvc8JICp3g) to ask questions regarding these recipes.

## Table of Contents
* Feature Profiling
    * pandas-profiling: [Notebook](https://github.com/rasgointelligence/feature-engineering-tutorials/blob/main/feature-profiling/pandas-profiling.ipynb) [Colab](https://colab.research.google.com/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-profiling/pandas-profiling.ipynb) [Jupyter Notebook Viewer](https://nbviewer.jupyter.org/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-profiling/pandas-profiling.ipynb)
    * SweetViz: [Notebook](https://github.com/rasgointelligence/feature-engineering-tutorials/blob/main/feature-profiling/SweetViz-profiling.ipynb) [Colab](https://colab.research.google.com/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-profiling/SweetViz-profiling.ipynb) [Jupyter Notebook Viewer](https://nbviewer.jupyter.org/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-profiling/SweetViz-profiling.ipynb)
    * pyrasgo: [Notebook](https://github.com/rasgointelligence/feature-engineering-tutorials/blob/main/feature-profiling/Pyaasgo-profiling.ipynb) [Colab](https://colab.research.google.com/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-profiling/Pyaasgo-profiling.ipynb) [Jupyter Notebook Viewer](https://nbviewer.jupyter.org/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-profiling/Pyaasgo-profiling.ipynb)
* Feature Transformation _(Coming soon)_
    * Time-series
      * Lag
      * Moving Average
* Feature Importance
  * Scikit-learn: [Notebook](https://github.com/rasgointelligence/feature-engineering-tutorials/blob/main/feature-importance/Sklearn%20Feature%20Importance.ipynb) [Colab](https://colab.research.google.com/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-importance/Sklearn%20Feature%20Importance.ipynb) [Jupyter Notebook Viewer](https://nbviewer.jupyter.org/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-importance/Sklearn%20Feature%20Importance.ipynb)
  * XGBoost: [Notebook](https://github.com/rasgointelligence/feature-engineering-tutorials/blob/main/feature-importance/XGBoost%20Feature%20Importance.ipynb) [Colab](https://colab.research.google.com/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-importance/XGBoost%20Feature%20Importance.ipynb) [Jupyter Notebook Viewer](https://nbviewer.jupyter.org/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-importance/XGBoost%20Feature%20Importance.ipynb)
  * catboost: [Notebook](https://github.com/rasgointelligence/feature-engineering-tutorials/blob/main/feature-importance/Catboost%20Feature%20Importance.ipynb) [Colab](https://colab.research.google.com/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-importance/Catboost%20Feature%20Importance.ipynb) [Jupyter Notebook Viewer](https://nbviewer.jupyter.org/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-importance/Catboost%20Feature%20Importance.ipynb)
  * pyrasgo: [Notebook](https://github.com/rasgointelligence/feature-engineering-tutorials/blob/main/feature-importance/Pyrasgo%20Feature%20Importance.ipynb) [Colab](https://colab.research.google.com/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-importance/Pyrasgo%20Feature%20Importance.ipynb) [Jupyter Notebook Viewer](https://nbviewer.jupyter.org/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-importance/Pyrasgo%20Feature%20Importance.ipynb)
* Feature Selection
  * Model Agnostic
      * Low Variance: [Notebook](https://github.com/rasgointelligence/feature-engineering-tutorials/blob/main/feature-selection/model-agnostic/Low%20Variance.ipynb) [Colab](https://colab.research.google.com/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-selection/model-agnostic/Low%20Variance.ipynb) [Jupyter Notebook Viewer](https://nbviewer.jupyter.org/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-selection/model-agnostic/Low%20Variance.ipynb)
      * Univariate Feature Selection
          * F-test: [Notebook](https://github.com/rasgointelligence/feature-engineering-tutorials/blob/main/feature-selection/model-agnostic/F%20Test.ipynb) [Colab](https://colab.research.google.com/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-selection/model-agnostic/F%20Test.ipynb) [Jupyter Notebook Viewer](https://nbviewer.jupyter.org/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-selection/model-agnostic/F%20Test.ipynb)
          * Mutual Information: [Notebook](https://github.com/rasgointelligence/feature-engineering-tutorials/blob/main/feature-selection/model-agnostic/Mutual%20Information.ipynb) [Colab](https://colab.research.google.com/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-selection/model-agnostic/Mutual%20Information.ipynb) [Jupyter Notebook Viewer](https://nbviewer.jupyter.org/github/rasgointelligence/feature-engineering-tutorials/blob/main/feature-selection/model-agnostic/Mutual%20Information.ipynb)
  * Model Based _(Coming soon)_
      * Lasso-based Selection
      * Feature Importance
          * Scikit-learn Tree-based
          * Tree-based
          * Permutation Importance
          * SHAP Values
      * Sequential Feature Selection
          * Stepwise Linear Regression
          * Forward Stepwise Selection
          * Backwards Stepwise Selection
          
