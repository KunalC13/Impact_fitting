# Impact_fitting

**[impact_experimental_class.ipynb]**(https://github.com/KunalC13/Impact_fitting/blob/main/impact_experimental_class.ipynb) contains the classification task which uses statistical features such as min, max, std, skewness, kurtosis and energy. 

**[impact_experimental_reg.ipynb]**(https://github.com/KunalC13/Impact_fitting/blob/main/impact_experimental_reg.ipynb) contains the regression task which uses statistical features such as min, max, std, skewness, kurtosis and energy. 

For both above tasks, I am getting accuracies close to the ones mentioned in the published paper with experimental data and also the draft of the paper with simulatiom data.

**[sim_exp_regression.ipynb]**(https://github.com/KunalC13/Impact_fitting/blob/main/sim_exp_regression.ipynb) contains the regression task which uses simulation data for training and experimental data for testing using the Difference in Time of Arrival features for which ToA has been calculated using Continuous Wavelet Transformation (CWT) for which I am not quite sure if this is the way to get ToA.