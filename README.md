# bmme_890_Anand
Contains file pertinent to work in bmme890 course- Machine Learning for Biosignal Analysis

## HW1-Setting up resources
Contains files for Homework 1 for BMME890 class.

computePD.m is a sample file that reads displacement data and outputs maximum displacement through time.

welcometogallippi.m introduces members of gallippi lab.

## HW2-Jupyter, Pandas and Kaggle and AlgebraRecap  
Intro to pandas and kaggle and review of algebraic operations in python.

## HW3-Initial Project Presentation
FD15_100Materials10Seeds.pkl which contains data from 10 Elasticities, 10 Viscosities, and 10 Realizations.

The Jupiter Notebook (Presentation1.ipynb) specifiles processing instructions using skikitlearn. Dependent images are contained in (presentation_images).

## HW4-Titanic Kaggle Competition
Kaggle link : https://www.kaggle.com/ksanand18

View Jupiter Notebook here if it does not automatically Render: https://nbviewer.jupyter.org/github/SilentAndromeda/TitanicKaggleSubmissions/blob/master/TitanicDataHW.ipynb

Several machine models were trained on the Titanic Kaggle data (train.csv) and evauluated with various metrics. K Nearest Neighbors was found to yield the highest mean cross val score and AUC, so the submission was generated using KNN on the test data. One-Hot Encoding was used to enconde the embarkation port, while cabin, passengerid, and name was dropped.

The Jupyper notebook walks one through the preprocessing and training.

## HW5-Housing Price Kaggle Competition
Jupyter Notebook file details how housing price data is cleaned and transformed, prior to training machine learning algorithms. The submission file, 'KA_HousePrice_Submission_RR.csv' was output from ridge regression and used as the final submission. Original test and train datasets are also included.

## HW6-Spike Sorting
Given an vector of neural amplitudes, spikes are extracted using varying signal windows and thresholds. The best unsupervisedlearning technique is determined following kmeans clustering. After the optimal cluster is found, the average waveform is ploted.

## HW7-Neural Networks
Neural networks are trained on the cifar10 dataset and the effects of kernel initialization, batch normalization, and activation functions are analyzed.

## Final Project
Data from ViSR simulations was split into 1D time series displacement vectors, as well 2D displacement images. The 1D data was fed into PCA-Regressor and fully connected network models while the 2D data was fed into the convolutional neural network models. The lowest RMSE acheived was with a Sigmoid Kernel PCA followed by KNN Regressor. 
