# Head_and-Neck(Hecktor21)_Survival_Analysis
We have analysis of head and neck cancer using Hecktor challenge 2021 dataset.

# 3D segmentation models for head and neck cancer segmentation.

In first part, we have trained various 3D segmentation models for head and neck cancer segmentation and in second part, we have developed
various feature extraction approach for survival days prediction

# Survival Days Prediction using various feature extraction methods
First we extracted radiomics features from 3D trained segmentation models and then passed these features to various Regressor models
such as Random Forest regressor, Gradient Boosting Regressor and so on.
Second, we have extracted features from 3D segmentation models from different levels and passed these features to the same regressor models
Third, we used clinical features for survival analysis
Fourth, we have combined all These features and used the same regressors for survival days predictions
