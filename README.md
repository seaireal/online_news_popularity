# Predicting the popularity of online news with article attributes

## Abstract

Driven by the interest of understanding what makes online news popular, we explored regression and classification methods to predict shares (log-transformed) and popularity using a wide variety of features related to these articles. For regression, linear model (stepwise selected), shrinkage methods (Ridge and Lasso), dimension reduction methods (PCR and PLS), as well as nonlinear models (GAMs with natural or smoothing splines) were attempted. For classification, logistic model (stepwise selected), Lasso-penalized logistic model, GAM logistic regression (with smoothing splines), LDA, QDA, KNN, and tree-based methods (such as classification tree, random forests, and boosting) were evaluated. The most noticeable feature identified by all methods is the average number of shares of an average keyword (kw_avg_avg). The time of publication also plays a key role: articles published on the weekends tend to generate more shares thus become more popular. This is consistent with the entertainment and leisure positioning of the news agency (Mashable) whose articles were examined in this study.

## Methods
* Regression
    * Linear regression using stepwise selection
    * Dimention reduction
        * Principal Components Regression (PCR)
        * Partial Least Squares (PLS)
    * Shrinkage
        * Ridge
        * Lasso
    * Nonlinear
        * Generalized Additive Model (GAM) with natural splines
        * GAM with smoothing splines
* Classification
    * Logistic regression
        * Logistic regression using stepwise selection
        * Lasso-penalized logistic regression
        * GAM logistic regression with smoothing splines
    * Linear Discriminant Analysis (LDA)
    * Quadratic Discriminant Analysis (QDA)
    * K-Nearest Neighbors (KNN)
* Tree-based methods
    * Decision Tree
    * Random Forest
    * Boosting



