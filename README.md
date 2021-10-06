

# Anomaly Detection using pycaret

`[Outlier Detection] (https://en.wikipedia.org/wiki/Anomaly_detection)`
(also known as *Anomaly Detection*) is an exciting yet challenging field,
which aims to identify outlying objects that are deviant from the general data distribution.
Outlier detection has been proven critical in many fields, such as credit card
fraud analytics, network intrusion detection, and mechanical unit defect detection.


## What is anomaly detection?

<p align="center">
  <img width="600" src="/anomaly_detection_example1.PNG" "Example of anomaly detection.">
</p>

Anomaly detection is a technique used to identify unusual patterns that do not conform to expected behavior, called outliers. Typically, this is treated as an unsupervised learning problem where the anomalous samples are not known a priori and it is assumed that the majority of the training dataset consists of “normal” data (here and elsewhere the term “normal” means *not anomalous* and is unrelated to the Gaussian distribution). [Lukas Ruff et al., 2018; Deep One-Class Classification]

In general, Anomaly detection is also called `Novelty Detection` or `Outlier Detection`, `Forgery Detection` and `Out-of-distribution Detection`.   

Each term has slightly different meanings. Mostly, on the assumption that you do not have unusual data, this problem is especially called `One Class Classification`, `One Class Segmentation`.  

<p align="center">
  <img width="600" src="/anomaly_detection_types.png" "Example of anomaly detection.">
</p>

and `Novelty Detection` and `Outlier Detection` have slightly different meanings. Figure below shows the differences of two terms.

Also, typically there are three types of target data. (`time-series data`, and `image data`, `video data`)  
In time-series data, it is aimed to detect a abnormal sections. 
In image, video data, it is aimed to classify abnormal images or to segment abnormal regions, for example, defect in some manufacturing data.  
