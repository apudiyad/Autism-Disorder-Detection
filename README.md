# Autism Spectrum Disorder Detection

## Abstract: 

Autistic Spectrum Disorder (ASD) is a neurodevelopment condition associated with significant healthcare costs, and early diagnosis can significantly reduce these. Unfortunately, waiting times for an ASD diagnosis are lengthy and procedures are not cost effective. The economic impact of autism and the increase in the number of ASD cases across the world reveals an urgent need for the development of easily implemented and effective screening methods. Therefore, a time-efficient and accessible ASD screening is imminent to help health professionals and inform individuals whether they should pursue formal clinical diagnosis. The rapid growth in the number of ASD cases worldwide necessitates datasets related to behaviour traits. However, such datasets are rare making it difficult to perform thorough analyses to improve the efficiency, sensitivity, specificity and predictive accuracy of the ASD screening process. Presently, very limited autism datasets associated with clinical or screening are available and most of them are genetic in nature. Hence, we propose a new dataset related to autism screening of adults that contained 20 features to be utilised for further analysis especially in determining influential autistic traits and improving the classification of ASD cases. In this dataset, we record ten behavioural features (AQ-10-Adult) plus ten individuals characteristics that have proved to be effective in detecting the ASD cases from controls in behaviour science.

## Data Type:

Multivariate OR Univariate OR Sequential OR Time-Series OR Text OR Domain-Theory-Nominal / categorical, binary and continuous.

## Task: 

Classification.

## Attribute Type: 

Categorical, continuous and binary.

## Area: 

Medical, health and social science.

## Format Type: 

Non-Matrix.

- Data set contains missing values.

- Number of Instances (records in your data set): 704.

- Number of Attributes (fields within each record): 21.

# Relevant Information:

## Relevant Papers:

Tabtah, F. (2017). Autism Spectrum Disorder Screening: Machine Learning Adaptation and DSM-5 Fulfillment. Proceedings of the 1st International Conference on Medical and Health Informatics 2017, pp.1-6. Taichung City, Taiwan, ACM.

Thabtah, F. (2017). ASDTests. A mobile app for ASD screening. www.asdtests.com [accessed December 20th, 2017].

Thabtah, F. (2017). Machine Learning in Autistic Spectrum Disorder Behavioural Research: A Review. To Appear in Informatics for Health and Social Care Journal. December, 2017 (in press)

## Data Source:

Fadi Fayez Thabtah,
Department of Digital Technology,
Manukau Institute of Technology,

Auckland, New Zealand

## Details about code:

### Modules to be installed: 
- numpy
- pandas
- from time import time\n",
- IPython.display
- seaborn
- matplotlib.pyplot
- sklearn.preprocessing.MinMaxScaler
-  sklearn.model_selection.train_test_split
-  sklearn.tree
-  sklearn.tree.DecisionTreeClassifier
-  pydotplus
-  IPython.display.Image
- sklearn.metrics
- sklearn.ensemble.RandomForestClassifier
- sklearn.metrics.fbeta_score
- sklearn.neighbors
- sklearn.naive_bayes.MultinomialNB
- sklearn.linear_model.LogisticRegression
- sklearn.metrics.accuracy_score
- sklearn.metrics.make_scorer
- sklearn.svm.SVC
- sklearn.model_selection.GridSearchCV
- sklearn.ensemble.GradientBoostingClassifier
- keras
- keras.models.Sequential
