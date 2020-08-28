# FIFA Young Talent Analysis


**FIFA player ratings are influenced by a big number of factors. Insights into these factors and prediction of the overall rating can be seen as a regression task. This analysis dives head first into this challenge through Jupyter Notebooks, drawing statistical inferences from data in an end-to-end manner, with pipelines for exploratory data analysis, data preparation and cleaning, and regression modeling.**

---

### Dataset


Obtained through [Kaggle](https://www.kaggle.com/stefanoleone992/fifa-20-complete-player-dataset), scraped from official servers, which contains over 100 features for around 18K players over 6 years.

---

#### Please use below links as notebooks might not render on Github.

* ## [Exploratory Data Analysis Notebook](https://nbviewer.jupyter.org/github/theavicaster/fifa-young-talent-analysis/blob/master/notebooks/EDAfifa20.ipynb)
![Plots](https://github.com/theavicaster/fifa-young-talent-analysis/blob/master/figures/comparisons.png)

### Frameworks used -

* PostgreSQL
* Pandas
* Seaborn
* Statsmodels

### Components -

* Univariate Analysis
  * Distribution Plots
  * Normality of Distributions
* Multivariate Analysis
  * Joint Scatter Plots
  * Categorical Plots
    * Violin Plots
    * Box Plots
  * Correlation Heatmaps
* Regression Analysis
  * Ordinary Least Square coefficients
  * Adjusted R-2 and tests of Statistical Significance


---

* ## [Data Preparation Notebook](https://nbviewer.jupyter.org/github/theavicaster/fifa-young-talent-analysis/blob/master/notebooks/DataPreparationAttackingRegressionFIFA20.ipynb)
![Correlations](https://github.com/theavicaster/fifa-young-talent-analysis/blob/master/figures/correlations.png)

### Frameworks used -

* SciPy
* Scikit-Learn

### Components -

* Linear Relationships
  * Pearson Correlation 
* Distribution Analysis 
  * Normality of Distributions
  * Data Transformations - Box-Cox
  * Residual Plot
* Joint Scatter Plots
  * Outlier Detection 
* Dimensionality Reduction 
  * Principle Component Analysis 
* Categorical Features
  * Feature Engineering 
  * Interaction Features 
  
---  
  
* ## [Regression Modeling Notebook](https://nbviewer.jupyter.org/github/theavicaster/fifa-young-talent-analysis/blob/master/notebooks/AdvancedRegressionFIFA20.ipynb)
![Results](https://github.com/theavicaster/fifa-young-talent-analysis/blob/master/figures/results.png)

### Frameworks used -

* Scikit-Learn
* XGBoost

### Components -

* Linear Approaches
  * Ordinary Least Squares
  * Regularized Linear Regression
  * Support Vector Regression
  * Bagging SVR and Lasso
* Tree Based Approaches
  * Decision Tree
  * Random Forest
  * Extremely Randomized Trees
* Boosting Approaches
  * Adaboost 
  * Extreme Gradient Boosting
*  Stacking Ensemble
  * Correlation of Predictions
  * XGBoost Metalearner
  * Error Analysis
