# AI_Team_23
This is our CPT_S_540 course project <br>

The whole process is done using the following files:
1.	N1_Spectral Analysis: In this file, the individual FTIR data files are combined to develop a dataset of 179 datapoints with 3406 features in the excel file named “Dataset O.xlsx” after the data analysis and outlier removal.
2.	N2_Preprocessing: In this file, several preprocessing methods utilized to remove the noise and new preprocessed dataset generated from this step.
3.	N3_Base Models: In this file, all dataset generated from original file and preprocessed are run on base model to get the best model for optimizing in later process.
4.	N4_Feature Selection: In this file, features are selected to reduce the time and space complexity on the best performed datasets.
5.	N5_Feature Extraction: In this file, features extraction was done to reduce the time and space complexity along with more meaning data on the best performed datasets.
6.	N6_Optimization: In this file, the best dataset and ANN model are optimized to produce the result with higher accuracy and lower space and time requirements.
7.	N6_Optimization_CNN: In this file, the best dataset and 1d-CNN model are optimized to produce the result with higher accuracy and lower space and time requirements.
8.	N6_Optimization_DNDT: In this file, the best dataset and DNDT model are optimized to produce the result with higher accuracy and lower space and time requirements.

The daataset are as follow:

Dataset O: Original dataset after the removal of outliers. It has 3406 features and 1 output. It has 179 datapoints.  <br>
Dataset P1: Preprocessed dataset with Baseline correction.  <br>
Dataset P2: Preprocessed dataset with SG Smoothing.  <br>
Dataset P3: Preprocessed dataset with Moving Average Smoothing.  <br>
Dataset P4: Preprocessed dataset with Multiplicative Scatter Correction (MSC).  <br>
Dataset P5: Preprocessed dataset with Extended Multiplicative Scatter Correction (EMSC).  <br>
Dataset P6: Preprocessed dataset with Standard Normal Variate (SNV). <br>
Dataset P7: Scaled dataset with Standardization.  <br>
Dataset P8: Scaled dataset with Min-max Normalization.
Dataset OFS: Dataset generated from selected features from original dataset.
Dataset PFS: Dataset generated from selected features from preprocessed dataset with SG smoothing (as it is the best dataset).
Dataset OFE: Dataset generated from extracted features from original dataset.
Dataset PFE: Dataset generated from extracted features from preprocessed dataset with SG smoothing (as it is the best dataset).

