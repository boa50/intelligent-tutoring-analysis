# Intelligent Tutoring Analysis
Nowadays, students have more access to technologies that help them with the everyday studies. Some systems help them to practice questions about a lot of disciplines.

The data analyzed here have information about patterns that students use to interact with a system that help them with the study of math.

This analysis tries to identify patterns that could help students while using the system.


## Installation
You can run the project using Docker containers.

There is a Dockerfile inside the container folder.

There is an example command at the notebooks_container_start.sh.sample file, that shows how to run the container.

There is a requiriments.txt file toghether with the Dockerfile, if you want to run the code a different way.

You must download the dataset from the official website. Instructions are placed iside the README.md filte in the dataset folder.


## Dataset
The dataset contains information about interactions between students and a tutoring system.

The interactions consists of users trying to answer math questions, each question could have one or more steps to be resolved.

The students could try to put the answers to the problems or ask for a hint.

The students are distributed by schools and classes.


## Project Organization
- container (folder): contains the files used to run the project using Docker containers and the requirements.txt with the dependences.

- dataset (folder): contains instructions on how to download and put the data the right way inside this folder.

- Analysis (Jupyter Notebook): the notebook containing all the code used during the analysis. The code is contained in a single file to make it easier to run all the code together.


## Acknowledgments
- We used the 'Assistments Math 2006-2007 (5046 Students)' dataset accessed via DataShop (pslcdatashop.web.cmu.edu).

- [Classification & Regression Evaluation Metrics](https://towardsdatascience.com/20-popular-machine-learning-metrics-part-1-classification-regression-evaluation-metrics-1ca3e282a2ce).

- [XGBoost Explanation](https://www.kaggle.com/dansbecker/xgboost/notebook).

- [Bayesian Optimization Explanation](https://aiinpractice.com/xgboost-hyperparameter-tuning-with-bayesian-optimization/).

- [BayesianOptimization Python Package](https://github.com/fmfn/BayesianOptimization).

- [Threshold Optimization](https://machinelearningmastery.com/threshold-moving-for-imbalanced-classification/).
