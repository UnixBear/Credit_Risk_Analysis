# Credit Risk Analysis

![title banner](https://performancecardservice.com/wp-content/uploads/2020/12/header-high-risk-payment-processing.jpg)

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes, the classes being legitimate transactions versus fraudulent ones. We'll use `imbalanced-learn` and `scikit-learn` libraries to build and evaluate models using resampling. 

Our data comes from the fictional LendingClub, a peer-to-peer lending services company; We'll oversample the data using the `RandomOverSampler` and `SMOTE` algorithms, and undersample the data using the `ClusterCentroids` algorithm.  Included is the dataset: `LoanStats_2019Q1.csv`

</br>

<a href="https://github.com/JovaniPink" rel="source">![Credit](https://raw.githubusercontent.com/JovaniPink/credit-risk-analysis/main/resources/models.png))</a>


Here is a breakdown of our work:
### Transformational steps:

- Identifying and handling the missing values (None)
- Encoding categorical variables with a mix of Pandas and  Scikit Learn's 'LabelEncoder'


### Splitting the data set:

- Feature scaling with StandardScaler
- Normalization

### Implement machine learning models:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine
- Gradient Boosting for classification

## Analysis

We had two methods of evaluation; re-sampling (making our minority and majority classes on some sort of par) and ensamble (where we pass decision making through nodes)


Best Peformance: Easy Ensemble AdaBoost Classifier. It has the highest scores from our classification reports.

Using Smote, we got the highest score for not only predicting high risk loans (which many of the other options were good at) but also predicting low risk scores (which many options did abysmally in finding).

