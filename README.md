## Spark-Customer-Churn-Prediction

Code used to predict customer churn for the fake company "sparkify" using spark on a standalone computer in local mode. Also included is the the blog post which is created from it's results. 

Table of Contents 
---

- [Installations](#installation)
- [Motivation](#motivation)
- [Files](#files)
- [Usage](#Usage)
- [Authors](#authors)
- [Acknowlegements](#acknowledgements) 

## Installation

This code has a number of required dependencies which have to be pre-installed to work. They include:

- SparkSession
- pandas
- matplotlib
- The pyspark script includse installation at beginning of all packages it requires. The required dataset cannot be included due to github file size rules but can be sourced via udacity and should be named - "mini_sparkify_event_data.json"
## Motivation 

The aim of the project was to illustrate how the use of pyspark can solve real world business problems which would often require the manipulation of big data. One such question is businesses wanting to predict and prevent customer churn using machine learning techniques. Using pyspark means that this can be done on a standalone computer on a subset of data before being scaled to work on a much larger dataset of all of a businesses customer interactions. Multiple machine learning approaches are illustrated and compared and their results documented within the blog post included in the repository - "Capstone_Project_Blog"

## Files 

In the repository two files are included:
- "Sparkify.ipynb" : A jupyter notebook including annotated pyspark code which reads, explores and models the above subset of data. 
- "Capstone_Project_Blog" : A blog post which describes the process of modelling usinbg pyspark and analyses the results the model produce. 
Data can be sourced via contacting UDACITY.
## Usage 
All code is annotated so that it is easy to understand and follow. The code reads the required data which is also included within the repository. 

## Authors

All code created by [Joshua Lindsay](https://github.com/josh-lindsay2023) following a Udacity template. 
All Data taken from UDACITY. 

## Acknowledegments

 Thanks to UDACITY for helping me develop my coding and data science knowledge to carry out this analysis. 
