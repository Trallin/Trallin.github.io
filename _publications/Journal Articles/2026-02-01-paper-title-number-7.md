---
title: "Optuna-CNN Based Proxy Model for Calculation of Perforating Shock Loads"
collection: publications
category: manuscripts
permalink: /publication/2026-01-01-paper-title-number-7
excerpt: 'An Optuna-optimized CNN proxy model for accurate prediction of perforating shock loads under complex deep-well and deep-sea conditions.'
date: 2026-01-01
venue: 'Geoenergy Science and Engineering'
doiurl: '[https://doi.org/10.1016/j.geoen.2026.214439](https://doi.org/10.1016/j.geoen.2026.214439)'
citation: 'Q. Deng, G. Qi, J. Jiang, D. Yang. (2026). "Optuna-CNN Based Proxy Model for Calculation of Perforating Shock Loads." <i>Geoenergy Science and Engineering</i>, 214439.'
---

Due to the complexity of deep-well, ultra-deep-well, as well as deep-sea and ultra-deep-sea conditions, perforating shock loads from combined perforation and well test system can easily damage the internal structure of the wellbore, posing a high level of safety risk. The calculation of perforating shock loads stands as a fundamental prerequisite for further comprehensive analysis of wellbore safety. Notably, prevailing calculation models predominantly rely on empirical formulations derived from explosive phenomena, necessitating a multi-parameter calculation method that aligns with practical conditions. Therefore, this study develops a Optuna-CNN based proxy model by utilizing perforating data generated from numerical simulation. Perforating models are structed to establishes a dataset that consists of perforation shock loads under different total explosive weights, initial wellbore pressure, wellbore explosive volume, detonation interval, and formation pressure. Then, the Pearson correlation coefficient is employed to ascertain the relationships between these parameters and perforating shock loads. Subsequently, the Optuna-CNN proxy model is developed with the hyperparameter optimization by Optuna framework, and the importance of hyperparameters is analyzed. Through comparison with 3 other common regression models (i.e., feedforward neural network, support vector machine, gradient boosted regression) using metrics such as MAE, MSE, R2, and MAPE, Optuna-CNN exhibits the best performance with the R2 of 0.9562. Subsequently, the Optuna-CNN proxy model is validated with measured data from two example wells. The results indicate the high accuracy of Optuna-CNN, revealing calculation errors of 3.35% and 3.28%, respectively.
