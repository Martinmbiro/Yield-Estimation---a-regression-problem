# Yield Estimation - a regression problem

<p align="center">
  <img src='pics/crops.jpg'  width='530'/>
</p>

Hello again 👋
+ **Crop yield estimation** is an agriculture-specific task, that is central to designing effective agricultural strategies and mainitaining food security. This repository is meant to illustrate that agriculture could leverage the power of Artificial Intelligence (AI) to make **data-informed** yield estimations.
+ The regression model built for this exercise was trained to estimate crop `Production` quantities based on 6 features (Crop type, Season, State, farm Area, Fertilizer, & Pesticide quantities)
+ If the model were deployed, a farmer would pass the 6 features describing their prevailing farming conditions. The `yield` is then calculated by dividing the estimated `Production` with farm `Area`
+ Yield estimation maps to a well-established concept in Machine Learning: **regression**. I illustrate implementing this concept in the notebooks _(labeled 01...03)_ by creating, training, and evaluating a **regression** model. Comments, working code, and links to the latest official documentation are included every step of the way
+ As always, feel free to build upon these concepts


## Milestones 🏁
**Concepts covered in this exercise include:**  
1. [x] Data wrangling, analysis and visualization
2. [x] Training and evaluating regression models ([`XGBRegressor`](https://xgboost.readthedocs.io/en/stable/python/python_api.html#xgboost.XGBRegressor) & [`RandomForestRegressor`](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html#randomforestregressor))

## Tools ⚒️
1. [`Google Colab`](https://colab.google/) - A hosted _Jupyter Notebook_ service by Google.
2. [`pandas`](https://pandas.pydata.org/docs/index.html) - An open-source data analysis and manipulation tool built on Python
3. [`scikit-learn`](https://scikit-learn.org/stable/#) - A free open-source library that offers Machine Learning tools for the Python programming language
4. [`matplotlib`](https://matplotlib.org/) - A comprehensive library for making static, animated, and interactive visualizations in Python
5. [`seaborn`](https://seaborn.pydata.org/) -  A Python data visualization library based on [`matplotlib`](https://matplotlib.org/), that provides a high-level interface for drawing attractive and informative statistical graphics
6. [`xgboost`](https://xgboost.readthedocs.io/) - An optimized _gradient boosting_ library
7. [`optuna`](https://optuna.readthedocs.io/en/stable/index.html) - An automatic hyperparameter optimization software framework designed for machine learning
8. [`numpy`](https://numpy.org/) - The fundamental package for scientific computing with Python

## Results 📈
> So, how well did the model estimate crop `Production` quantities from unseen data?
+ On a scale of `0` to `1.0`, [`r2_score`](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.r2_score.html#sklearn.metrics.r2_score) of `0.93`
+ [`mean_absolute_error`](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_error.html#sklearn.metrics.mean_absolute_error) of `11,557.52`

## Reference 📚
+ Thanks to the insight gained from [`Microsoft Learn`](https://learn.microsoft.com/api/achievements/share/en-us/MartinMuriithi-6560/NZ987NAF?sharingId=C156514E494249EC), [`datacamp`](https://www.datacamp.com), and [`medium`](https://medium.com)
+ Not forgetting these gorgeous gourgeous [`emojis`](https://gist.github.com/FlyteWizard/468c0a0a6c854ed5780a32deb73d457f) 😻

> _Opensource dataset by [`Kaggle`](https://www.kaggle.com/datasets)_ ♥  
> _Illustration by [`Storyset`](https://storyset.com)_ ♥

