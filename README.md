# Building-a-best-performing-model-for-tabular-data/ Housing Price Prediction

My work was the best-performing shared notebook among over 80 thousand trials in Kaggle's machine-learning competition for housing price prediction.

I believe approach on this work could be a baseline for a generalized standard practice for mixed-type small-size data sets.

You can find the original notebook at this link: https://www.kaggle.com/code/rzatemizel/feature-engineering-optuna-stacked-pipe

GitHub has a known problem when rendering jupyter notebooks; this makes some output cells in notebook quite ugly.
You can also find a complete notebook with better quality on this link: https://nbviewer.org/github/rizatemizel/Building-a-best-performing-model-for-tabular-data-sets/blob/main/feature-engineering-optuna-stacked-pipe.ipynb

Based on this work, I also prepared an end-to-end machine learning project deployed on AWS Elastic Beanstalk. If you are interested, please check this repo for this project: https://github.com/rizatemizel/machine_learning_deployment_elastic_beanstalk/tree/main

## Model Development Approach

This work benefits best practices posted by the Kaggle community but differentiates itself with the following:

- Extensive EDA and feature engineering

Numerical Features             |  Categorical Features  
:-------------------------:|:-------------------------:
![numerical](https://github.com/rizatemizel/Building-a-best-performing-model-for-tabular-data-sets/assets/127015640/23d3a3b1-7b87-4793-9de4-9b4ebdcdb311) | ![categorical](https://github.com/rizatemizel/Building-a-best-performing-model-for-tabular-data-sets/assets/127015640/7d438af5-2c79-4112-b290-f5c27f069660)


- Almost an obsession with doing everything in a pipeline, including feature engineering, preprocessing, and hyperparameter tuning

You can observe a snapshot of the pipeline below. It's capable of preprocessing, feature engineering, and serving predictions.

![pipeline](https://github.com/rizatemizel/ml_deployment/assets/127015640/e80b8e2f-eb3e-400c-b152-75f1c7f3a085)

- An aggressive hyperparameter search for base models in an ensemble with Optuna package.

It demonstrates how to perform a Bayesian hyperparameter optimization using Optuna package on a complete scikit-learn pipeline.

Hyperparameter Optimization             |  Hyperparameter Importance
:-------------------------:|:-------------------------:
![optuna1](https://github.com/rizatemizel/Building-a-best-performing-model-for-tabular-data-sets/assets/127015640/d8a39d5a-65a5-4f1a-aee1-0f8b68674e03) | ![optuna2](https://github.com/rizatemizel/Building-a-best-performing-model-for-tabular-data-sets/assets/127015640/72617537-8730-4afc-89fb-bbd5c4892be5)



## Tech Stack


- Python, Pandas, Scikit-learn, Seaborn, Optuna, Xgboost, Catboost, LightGBM





