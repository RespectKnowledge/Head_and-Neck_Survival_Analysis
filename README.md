# Head_and-Neck(Hecktor21)_Survival_Analysis
We have analysis of head and neck cancer using Hecktor challenge 2021 dataset.

# 3D segmentation models for head and neck cancer segmentation.
# HeadandNeck21_3D_Segmentation
Head and Neck tumor segmentation using PET/CT based on 3D deep learning segmentation models
# download the dataset from the following hector21 challenge website
https://www.aicrowd.com/challenges/miccai-2021-hecktor

The proposed 3D model look like this

![3Dmodel](https://user-images.githubusercontent.com/46267777/135850649-57ad3a9a-0bc8-4a89-bd0e-dd84a0aeb63e.png)

supproting modules used in main proposed model

![3Dpng_1](https://user-images.githubusercontent.com/46267777/135851059-87303e6f-e83c-42b2-854e-590dda745c0b.png)

3D ResNet Module

![3Dmodel_resnet](https://user-images.githubusercontent.com/46267777/135851531-2656d0fb-ec8d-4d23-bed0-066692b3ee69.png)

3D Inception Module

![3DInception_module](https://user-images.githubusercontent.com/46267777/135851734-a5c6c973-bab1-4026-b210-09691bb92e2f.png)


In first part, we have trained various 3D segmentation models for head and neck cancer segmentation and in second part, we have developed
various feature extraction approach for survival days prediction

# Survival Days Prediction using various feature extraction methods
First we extracted radiomics features from 3D trained segmentation models and then passed these features to various Regressor models
such as Random Forest regressor, Gradient Boosting Regressor and so on.
Second, we have extracted features from 3D segmentation models from different levels and passed these features to the same regressor models
Third, we used clinical features for survival analysis
Fourth, we have combined all These features and used the same regressors for survival days predictions
