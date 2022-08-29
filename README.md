# Credit Risk Analysis

![title banner](https://performancecardservice.com/wp-content/uploads/2020/12/header-high-risk-payment-processing.jpg)

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes, the classes being legitimate transactions versus fraudulent ones. We'll use `imbalanced-learn` and `scikit-learn` libraries to build and evaluate models using resampling. 

Our data comes from the fictional LendingClub, a peer-to-peer lending services company; We'll oversample the data using the `RandomOverSampler` and `SMOTE` algorithms, and undersample the data using the `ClusterCentroids` algorithm.  Included is the dataset: `LoanStats_2019Q1.csv`