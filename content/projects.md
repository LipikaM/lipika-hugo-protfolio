---
title: "Projects"
date: 2020-07-16T16:15:26+02:00
draft: true
---

## * Autonomous driving : AWS Deepracer

** Synopsis **: AWS deepracer is an IOT enabled autonomous vehicle workshop organised by AWS and Adidas AG.
As part of this hackathon/ project, I have implemented the reinforcement algorithm for autonomous vehicle with line sensing capability.
Detail implementation about the peoject can be found here.

https://github.com/murari-goswami/aws-deepracer.git

** Technologies **: AWS SDK, Python, AWS Deepracher SDK

------
------

## * Kaggle Competitions:
#### 2.1 Categorial Feature Encoding challange - II

** Synopsis **: As part of this kaggle challange, I have implemented feature encoding of categorial values and use them for EDA. 
It covers all 3 level of encoding viz - One hot encoding, label encoding, binarization techniques. Eventually created the model for one hot encoding. Details about the project work is avaibale in the below github link below. This is a documented jupyter notebook with all necessary details.

https://github.com/murari-goswami/kaggle-Categorical-Feature-Encoding-Challenge-II.git

** Technologies **: IPython notebook, Python, pandas, numpy, matplotlib, seeborn

------

#### * Coronavirus Exploratory Data Analysis and Forecasting (using facebook's prophet)

** Synopsis **: As part of this kaggle challange, I have implemented a time series analysis and prediction using facebook's prophet library for Corona Virus (COVID19) confirmed, death and recover cases from WHO data preserved in kaggle platform.
An associated kaggle kernel is as below

https://www.kaggle.com/goswamimurari/germany-coronavirus-eda-forecast-prophet

** Technologies **: IPython notebook, Python, facebook prophet - probabilistic time series model

------

#### * NOAA - open source weather EDA

** Synopsis **: As part of this kaggle challange, I have implemented an EDA for NOAA weather data for last 70 years and check for adidas stores weather analytics in adidas store locations.

https://www.kaggle.com/goswamimurari/aws-noaa-weather-on-adidas-store-location-eda

** Technologies **: IPython notebook, Python, pandas, numpy, matplotlib, seeborn

------
------

## * M3D Adidas

M3D stands for Metadata Driven Development and is a cloud and platform agnostic framework for the automated creation, management and governance of metadata and data flows from multiple source to multiple target systems. The main features and design goals of M3D are:

Cloud and platform agnostic
Enforcement global data model including speaking names and business objects
Governance by conventions instead of maintaining state and logic
Lightweight and easy to use
Flexible development of new features
Stateless execution with minimal external dependencies
Enable self-service
Possibility to extend to multiple destination systems (currently AWS EMR)
M3D consists of two components. m3d-api which we're providing in this repo, and m3d-engine containing the main logic using Apache Spark.

Use cases
M3D can be used for:

Creation of data lake environments
Management and governance of metadata
Data flows from multiple sources
Data flows to multiple target systems
Algorithms as data frame transformation

https://github.com/adidas/m3d-api
https://github.com/adidas/m3d-engine

** Technologies **: Python, Spark, Scala, Jenkins,  Docker

------
------

## * Spark distributed container

The repo can spin spark distributed network for multiple nodes as docker containers. It can mount test data and load spark algorithms/ ML models and execute different tests. The default is a single node cluster with 1 master. However, in order to fully utilise the power of multiple worker nodes, scale feature of docker-compose can be utilised to ramp up cluster with multiple nodes.

https://github.com/murari-goswami/spark-container

** Technologies **: Docker, Spark, Scala, Shell

------
------

## * BigDataToolSuite

A set of Tool Suite created to facilitate the traditional RDBMS DW migration to Low Cost infrastructure with Hadoop architecture. This git Hub repository contains all such tools crated, tested and used during the migration phase. Mainly created with Java,Python, Apache POi, Tika, Pig, Hive these are ready to run utilities in any flavour of RED Hat Linux and Cloudera CDH clusters set up.

https://github.com/murari-goswami/BigData-ToolSuite

** Technologies **: Docker, Java,Python, Apache POi, Tika, Pig, Hive


## * Telecom consumer Data Usage Analysis

Customer data usage pattern analysis is done from the call data records generated from a billing platform. Transform them and henceforth analyse them through Map reduce, Pig and Hive wherever applicable. The customer usage pattern from the call data records generated from a billing platform. This artefact will give details of the different data inputs categorised into dimension and fact tables. The idea of this analysis to devise customer profiling and usage pattern across different dimensions.
A chain of ETL process to load data into fact tables and populate the dimension tables. At the final product, a data cube will be generated. Various data analysis i.e. drill down, slicing, dicing can be done on this data cube and required report can be generated through it.

Customer Profiling:
 Gender wise service usage classification and volumetric analysis  Gender wise Billed Unit Volumetric Analysis  Measure of international call data across geography
Customer Usage Pattern Analysis
 Analytic - to find Country wise- offer (Bolton Name) – Volume of Billed Units.  Usage and revenue analytic across dimensions on service type and plan.  Nature of outgoing calls (i.e. Fixed Landline, Emergency Number, Utility Number, )  Rate plan analysis.  Gender across Money spend pattern analysis

** Technologies **: Pentaho Kettle,Spoon and PRD -  https://github.com/murari-goswami/Pentaho-ETL-on-Telco-CDR 
** Technologies **: Big Data, Hadoop, Hive, Map Reduce -  https://github.com/murari-goswami/Hadoop-MapReduce-Telecom-CDR-Analytics-Use-Case