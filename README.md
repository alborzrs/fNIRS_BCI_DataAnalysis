# fNIRS_BCI_DataAnalysis
Preprocessing, feature extraction (slopes, moving slopes, Kurtosis, skewness, mean and variance)  and classification codes (regularized LDA and SVM) for analyzing fNIRS (functional near-infrared spectroscopy) data for brain-computer interfaces (BCIs). All the codes are written in MATLAB.

List of functions:

--> f_FilteredDataMatrixtoFeatures_NIRS
This function converts raw fNIRS data to a matrix of features. 

-->f_FilteredDataMatrixtoFeatures_NIRS
This function transforms the raw (or filtered) input fNIRS data to a feature matrix, including the common fNIRS feature types: mean, variance, skewness, Kurtosis, max moving slope (in a specified window size). 
