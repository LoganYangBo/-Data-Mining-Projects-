# -Data-Mining-Projects-
Course 5243 Data Mining Projects

Projection1:

This homework will focus on a modified version of the kaggle dataset "Pima Indians Diabets Database". It can be found here. The overarching objective is to diagnostically predict whether or not a patient has diabetes based upon several other covariates. The full description is shown on the website.
Your task will be to first: 
1) Do the prerequisite EDA to understand the data set you will be working on.
2) Fit an appropriate logistic model and analyze it.
While some of the questions have exact answers, a few others are more open to interpretation. However, what we're looking for is the correct thinking and analysis. For the objective questions, while some points are awarded for "the correct number", the majority of the points will be awarded for a proper analysis and logical investigation.

Projection2:

In this lab, you will use the "Cleveland Data CLEANED AND TRIMMED.csv" heart disease dataset provided on Carmen. It is a subset of the "Cleveland" dataset that can be found here: https://archive.ics.uci.edu/ml/datasets/Heart+Disease. You will configure, execute, and evaluate an off-the-shelf K-Nearest-Neighbor classifier and two other classifiers you choose.The objectives of this assignment are: Understand how to evaluate classifiers based on business criteria. Understand how to tune and evaluate a classifier to achieve good performance. Understand how to select and evaluate suitable off-the-shelf classifiers based on the characteristics of a dataset and the outcomes you need.
You work for a medical institution that wants to improve the heart health of its patients. You have obtained a dataset that contains a variety of demographic and health-related information for a group of patients. It also includes a CLASS variable "num" that indicates the heart health of each of the patients. The values are:
No heart health issues / risk
Slight heart health issues / risk
Moderate heart health issues / risk
High heart health issues / risk
Extreme heart health issue / risk
You have been asked to develop a classifier based on the dataset data, to predict the CLASS of new patients so they can be enrolled in interventions based on their demographic data.
The COSTs of the interventions are as follows, based on the predicted class of each patient
0) Tiny intervention: 100 (dollars) 1) Minor intervention: 200 2) Moderate intervention: 300 3) Significant intervention: 400 4) Extreme intervention: 500
The BENEFITs of the interventions are as follows:
If the classification is correct and the correct intervention given to the patient: 500 * (TRUE_CLASS + 1)
If an incorrect classification is made and the wrong intervention is given to the patient: 0
You would like to find a classifier that maximizes the overall NET_BENEFIT = BENEFIT - COST. Therefore, a larger positive number is a good outcome.
So, for example:
If a patient's true class is 4 and their predicted class is 0, their NET_BENEFIT = 0 - 100 = -100
If a patient's true class is 4 and they are correctly classified, their NET_BENEFIT is 500*(4+1) - 500 = 2000
The medical institution would like you to evaluate the use of a K-Nearest-Neighbor classifier as a starting point. You agree to do so, as long as you then can choose a different classifier if you are not satisfied with KNN.

Projection3:

In this lab, you will perform clustering on three datasets. Your will choose suitable clustering algorithms, evaluate them on the datasets, and compare their performance.
Datasets:
The file small_Xydf.csv is a two-dimensional dataset with 200 records. It contains columns X0, X1, and y. The y column is the actual cluster number that was produced by the dataset generation algorithm. Do not use it for the clustering algorithm. It will be used to evaluate your clustering algorithm below.
The file large1_Xydf.csv is a two-dimensional dataset with 3000 records. It contains columns X0, X1, and y. The y column is the actual cluster number that was produced by the dataset generation algorithm. Do not use it for the clustering algorithm. It will be used to evaluate your clustering algorithm below.
The file large2_Xydf.csv is another two-dimensional dataset with 3000 records, and characteristics different from the “large1” dataset. It contains columns X0, X1, and y. The y column is the actual cluster number that was produced by the dataset generation algorithm. Do not use it for the clustering algorithm. It will be used to evaluate your clustering algorithm below.
Approach:
This homework makes use of the Clustering Algorithms offered by the SciKitLearn Library. Study the information at https://scikit-learn.org/stable/modules/clustering.html. Follow the guidance in the individual sections below.
