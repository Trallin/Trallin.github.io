---
title: "Optuna-CNN Based Proxy Model for Calculation of Perforating Shock Loads (Under Review)"  
collection: publications  
category: preprints  
permalink: /publication/2024-03-01-paper-title-number-1
excerpt: 'Proposes a hybrid Optuna-CNN model to predict perforation-induced shock loads, enhancing computational efficiency.'
# date: 2024-03-01  
# venue: 'Under Review'  
doiurl: 'http://dx.doi.org/10.2139/ssrn.4752997'  
---

Due to the complexity of deep-well, ultra-deep-well, as well as deep-sea and ultra-deep-sea conditions, perforating shock loads from combined perforation and well test system can easily damage the internal structure of the wellbore, posing a high level of safety risk. The calculation of perforating shock loads stands as a fundamental prerequisite for further comprehensive analysis of wellbore safety. Notably, prevailing calculation models predominantly rely on empirical formulations derived from explosive phenomena, necessitating a multi-parameter calculation method that aligns with practical conditions. Therefore, this study develops a Optuna-CNN based proxy model by utilizing perforating data generated from numerical simulation. Perforating models are structed to establishes a dataset that consists of perforation impact loads under different total explosive weights, initial wellbore pressure, wellbore explosive volume, detonation interval, and formation pressure. Then, the Pearson correlation coefficient is employed to ascertain the relationships between these parameters and perforating shock loads. Subsequently, the Optuna-CNN proxy model is developed with the hyperparameter optimization by Optuna framework, and the importance of hyperparameters is analyzed. Through comparison with 3 other common machine learning models (i.e., feedforward neural network, support vector machine, gradient boosted regression) using metrics such as MAE, MAPE, R2, and RMSE, Optuna-CNN exhibits the best performance. Subsequently, the Optuna-CNN proxy model is validated with measured data from two example wells. The results indicate the high accuracy of Optuna-CNN, revealing calculation errors of 1.65% and 1.71%, respectively.