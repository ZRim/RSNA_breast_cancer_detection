# RSNA_breast_cancer_detection
This project is a kaggle competition. The aim is to detect breast cancer base on mammography images. 

The link of the competition is 
https://www.kaggle.com/competitions/rsna-breast-cancer-detection/overview

The dataset is available in this link
https://www.kaggle.com/competitions/rsna-breast-cancer-detection/data

The files RSNA_Baseline contain the Pytorch Baseline for traning and inference. It is useful for a beginner.

The file RSNA_training_V0 contains the training code with a simple model Resnet (does not give a good score), and without using train_test_split from sklearn.

The file RSNA_training_V1 contains the training code with Efficient model and using train_test_split from sklearn.

The file RSNA_training_V2 contains the training code with Efficient model and with possibility of dividing data into folds.

The file preprocess-images-rsna contains the code that allows preprocessing the images to be used in the training process.

The file rsna-inference is used for the inference in Kaggle.


