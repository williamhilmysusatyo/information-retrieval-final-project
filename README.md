# Implementation of BM25 Algorithm for Search Engine Development of app.rekmed.com

* Haikal Muhammad Zahid Ghiffari - (21/472762/PA/20332)
* Muhammad Rifki Aprinanda Putra - (21/477836/PA/20707)
* Veronika Regina Shanty Ocviyanti P. - (20/454543/PA/19574)
* William Hilmy Susatyo - (21/472585/PA/20308)


## Overview
The research presented in this repository utilizes the BM25 Algorithm to create a ranked retrieval system from the dataset of app.rekmed.com, an integrated medical platform. The proper preprocessing method, such as forward imputation, and feature engineering technique, which includes cardinality reduction, are performed to ensure that the resulting ranked retrieval produces reliable results. 

Recent findings suggest that the performance metrics of the method is highly dependent on the given query. Nevertheless, the result from most of the queries indicates that the precision tends to be lower as the document that is taken into consideration becomes greater, while the opposite occurs for the recall. The reason lies in the nature of precision, where a broader set of items is taken into account, making it increasingly difficult for all of them to be genuinely relevant. In contrast, recall tends to rise with a larger top K since it gauges the model's effectiveness in capturing as many pertinent items as possible.



## Features
The features provided in this ranked retrieval system consist of as follows:
- Search anything related to the doctor, patient, and treatment
- Search the doctor that handles particular patient
- Search list of patients that took particular treatment
- Search list of treatment that could be done by particular doctor
- Search list of doctor that took particular treatment

## Tools
- Python
- Jupyter Notebook
- Library:
  * Pandas
  * Matplotlib
  * Sklearn
  * Numpy
  * BM25
