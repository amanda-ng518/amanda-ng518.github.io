---
title: "Aspects of Robust Regression Analysis"
excerpt: '<p><i>Supervised by Prof. Nancy Reid, Summer 2024 - Winter 2026 </i></p>

UTEA, SURA Research Student, UofT DoSS'
collection: portfolio
---
Linear regression estimators are known to be sensitive to outliers, and one alternative to obtain a robust and efficient estimator of the regression parameter is to model the error with Student's $t$ distribution.  In this article, we compare estimators of the degrees of freedom parameter in the $t$ distribution using frequentist and Bayesian methods, and then study properties of the corresponding estimated regression coefficient. We also include the comparison with some recommended approaches in the literature, including fixing the degrees of freedom and robust regression using the Huber loss. 
Our extensive simulations on both synthetic and real data demonstrate that estimating the degrees of freedom via the adjusted profile log-likelihood approach yields regression coefficient estimators with high accuracy, performing comparably to the maximum likelihood estimators where the degrees of freedom are fixed at their true values. These findings provide a detailed synthesis of $t$-based robust regression and underscore a key insight: the proper calibration of the degrees of freedom is as crucial as the choice of the robust distribution itself for achieving optimal performance. 

Click [manuscript](https://arxiv.org/abs/2603.00269), [project GitHub page](https://github.com/amanda-ng518/Aspects-of-Robust-Regression-Analysis), [R package](https://github.com/amanda-ng518/RobustTRegression) to view it.
