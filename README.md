# Master Thesis
This repo contains the code for my Master Thesis: "Estimating the Distribution of Organic Aerosol in Europe: With Applications of Conformal Prediction".

The code is articulated as follows:

- (1) EDA: Exploratory analysis of the available data, some map visualization and feature engineering of geo-spatial data.
- (2) CAMx Performance: Exploratory analysis of the performance of the CAMx simulator.
- Estimate_c: Estimation of conversion factor between OC and OA.
- Predict Performance: Regression-Bias analysis.
- Local Bias: Regression-Bias analysis performed at individual stations.
- DS at seen locations: Statistical down-scaling of OA at seen location with ML-models.
- CP at seen locations: Conformal Prediction for DS at seen locations.
- DS at unseen locations: Statistical down-scaling of OA at seen location with ML-models.
- DS OA components: Statistical down-scaling of OA components at seen location with multi-output Random Forest.
- CP at unseen locations: Conformal Prediction for DS at unseen locations.
- PPI_CAMx: proof-of-concept application of Prediction-Powered Inference with CAMx data.
- ppi: auxilary function for computing PPI in PPI_CAMx.
- utils_ppi: auxilary function for plotting in PPI_CAMx.
- down-boxplot: code for boxplots of down-scaling at seen locations.
- utils_CP: code for some figures of Chapter 3 on Conformal Prediction.
 


