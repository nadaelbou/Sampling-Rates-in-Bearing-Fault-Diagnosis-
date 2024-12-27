# Multi-Rate Resampling of Vibration Signals

In this repository, the codes related to the paper 'Multi-Rate Vibration Signal Analysis for Bearing Fault Detection in Induction Machines Using Supervised Learning Classifier' (doi: https://doi.org/10.3390/machines12010017) are given.

## Dataset
The dataset is the famous open source CWRU dataset for bearing fault diagnosis. Further explanation related to the set-up and experiments are explained in the following link: https://engineering.case.edu/bearingdatacenter/download-data-file. The data are provided in .mat file (MATLAB format) but can be easily read on Python. 

The architecture of the data used in the article is detailed in the article. 

## Algorithms 
In this folder, you can find the algorithms written on MATLAB and Python (ran on Kaggle as I could use their accelerators' settings). The following codes are provided:
1. Pre-processing and feature extraction: this step is done on MATLAB as I used their resample() function as explained in the paper. The code will output a .mat file with all features at a certain sampling rate obtained. 
2. The Python script will load the data (acknowledging you've changed the folder path) and train ML models at different sampling frequency.

## Algorithms 
For any question, feel free to reach the first author. 
