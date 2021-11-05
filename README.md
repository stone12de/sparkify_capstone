# sparkify_capstone
This is the capstone project of my Nanodegree "Data Science" using Python and Spark.

## Introduction:
In the last years, the medium of music distribution industrie has shifted from CDs to sharing platforms like youtube music and spotify.
These music sharing companies have an rapidly growing sales return. So, for these companies its crucial to recruit customers and to keep them with their service.
In this context a model, which can classify a possible churn would be a hugh benefit, as countermeasures would be possible.
Based on a dataset, which describes the interaction between customer, which either rejected the service or stayed with the service, and the music sharing platform, such a churn-prediction-model has been implemented and tested successfully.
As the original data set is relatively large, both data preparation and model creation will be done using SPARK, so that the data can be distributed on a scalable set of computers.

## Installations:
python 3.6.3  
pyspark 2.4.3  
pandas 0.23.3  
numpy 1.12.1  
seaborn 0.8.1  
matplotlib 2.1.0  

## Conclusion:
We made 3 general steps to find a suitable classifier to detect churn within the users:
getting a deeper understanding of the data provided,
design a useful set of features
build, test and compare different kinds of classifier-models to find the optimum.

Sufficient results have been achived, however some improvements would be possible:
We could test other models like Gradient Boosted Tree Classifier and check other hyper parameters to get better results.
Apart from this, we also could spend more effort in feature engineering, to extract more relevant information from the given data.
So, despite of the achived results, there is still room for further improvements.

## Blog on Medium:
[detecting user churn from music share platform](https://medium.com/p/9e2fc8b3750d/edit)
