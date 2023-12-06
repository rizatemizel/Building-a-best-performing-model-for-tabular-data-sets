# Building-a-best-performing-model-for-tabular-data/ Housing Price Prediction

My work was the best-performing shared notebook among over 80 thousand trials in Kaggle's machine-learning competition for housing price prediction.

I believe my approach on this work could be a baseline for a generalized standard practice for mixed-type small-size data sets.

You can find the original notebook at this link: https://www.kaggle.com/code/rzatemizel/feature-engineering-optuna-stacked-pipe

GitHub has a known problem when rendering jupyter notebooks; this makes some output cells quite ugly.
You can also find a complete notebook with better quality on this link: https://nbviewer.org/github/rizatemizel/Building-a-best-performing-model-for-tabular-data-sets/blob/main/feature-engineering-optuna-stacked-pipe.ipynb

Based on this work, I also prepared an end-to-end machine learning project deployed on AWS Elastic Beanstalk. Please check this repo for this project: https://github.com/rizatemizel/machine_learning_deployment_elastic_beanstalk/tree/main
## Model Development Approach

This work benefits the best preprocessing and feature engineering practices posted by the Kaggle community but differentiates itself with the following:

- Almost an obsession with doing everything in a pipeline, including feature engineering, preprocessing, and hyperparameter tuning
- An aggressive hyperparameter search for base models in an ensemble with Optuna package
- Extensive feature engineering not included in others' works.

You can observe a snapshot of the pipeline below. It's capable of preprocessing, feature engineering, and serving predictions.

![pipeline](https://github.com/rizatemizel/ml_deployment/assets/127015640/e80b8e2f-eb3e-400c-b152-75f1c7f3a085)


If you check the notebook, you can also observe that:

- Extensive exploratory data analysis is included

- Rigorous data processing is performed. And necessary actions are taken to eliminate any data leakage.

- It also demonstrates how to perform a Bayesian hyperparameter optimization using Optuna package on a complete scikit-learn pipeline.


## Tech Stack


- Python, Pandas, Scikit-learn, Seaborn, Optuna, Xgboost, Catboost, LightGBM





