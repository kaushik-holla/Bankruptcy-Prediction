# Bankruptcy-Prediction

1 Abstract

Bankruptcy prediction is the task of predicting bankruptcy and various measures of nancial distress of
rms. The prediction of bankruptcy in companies is a problem that has concerned entrepreneurs, researchers
and even governments for years, since detecting early signs that a company is going to enter bankruptcy
involuntarily and being able to save it from that process, can help reduce the economic losses that bankruptcy
entails, both in quantitative and qualitative terms. A business condition of either a small or large rm
concerns local community, industry participants and investors, but also in
uences policy makers and the
global economy and we aim to tackle this problem by developing a predictive model that combines various
econometric parameters which allow foreseeing the nancial condition of a rm.

2 Introduction
2.1 Dataset
We have chosen the Polish bankruptcy data, hosted by the University of California Irvine (UCI) Machine
Learning Repository. The dataset is about bankruptcy prediction of Polish companies. The data was collected
from Bankruptcy Prediction: Mining the Polish Bankruptcy Data Emerging Markets Information
Service (EMIS), which is a database containing information on emerging markets around the world. The
bankrupt companies were analyzed in the period 2000-2012, while the still operating companies were evaluated
from 2007 to 2013. The dataset is very apt for our research about bankruptcy prediction because it has
highly useful econometric indicators as attributes (features) and comes with a huge number of samples of
Polish companies that were analyzed in 5 dierent time-frames: Based on the collected data ve classication
cases were distinguished, that depends on the forecasting period:
1. 1st year: The data contains nancial rates from 1st year of the forecasting period and corresponding
class label that indicates bankruptcy status after 5 years.
2. 2nd year: The data contains nancial rates from 2nd year of the forecasting period and corresponding
class label that indicates bankruptcy status after 4 years.
3. 3rd year: The data contains nancial rates from 3rd year of the forecasting period and corresponding
class label that indicates bankruptcy status after 3 years.
4. 4th year: The data contains nancial rates from 4th year of the forecasting period and corresponding
class label that indicates bankruptcy status after 2 years.
5. 5th year: The data contains nancial rates from 5th year of the forecasting period and corresponding
class label that indicates bankruptcy status after 1 years.

2.2 Proposed Methodologies
In this project we plan to utilize Supervised Machine Learning techniques to reach our goals. The tentative
project plan could be segregated into the following steps:
 EDA (Exploratory Data Analysis): To analyze patterns within the data,extract dependencies,
compare correlations, identify missing values and recognize imbalances if any and use suitable techniques
like mean Imputation,k-nearest neighbors imputation,undersampling, SMOTE analysis, etc. to
tackle them.
 Training Models: We will train various classication techniques on our data to achieve the task of
completing our objective of predicting bankruptcy of a given company. The techniques which we plan
to implement are:
1. Gaussian Nave Bayes
2. Logistic Regression
3. Support Vector Machines
4. Articial Neural Networks

 Result Comparison and Conclusion: The results obtained in the previous step will be compared
utilizing various accuracy metrics to identify which method performed the best on the chosen dataset.
The eects of hyper-parameter tuning will be examined to further solidify our comparison results.

References
[1] The dataset can be found at https://archive.ics.uci.edu/ml/datasets/Polish+companies+
bankruptcy+data
[2] Wikipedia contributors. "Bankruptcy prediction". Wikipedia, The Free Encyclopedia, https://en.
wikipedia.org/wiki/Bankruptcy_prediction
