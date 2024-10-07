<H2 align='center'> Advanced Machine Learning - Final Project </H2>
<H3 align='center'> Trajectory Clustering in Vehicle Telematics Data </H3>

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python Version](https://img.shields.io/badge/python-3.7%20|%203.8-blue.svg)


Welcome to your capstone project for the Advanced Machine Learning course. This project aims to bridge theory and practice by applying ML techniques to real-world telematics data collected from MEMS (Micro-Electro-Mechanical Systems) sensors in vehicles. You will engage in a comprehensive analysis that includes data preprocessing, exploratory data analysis, distance metrics for trajectories, modeling, and interpretation of results. This project is designed to reinforce your understanding of machine learning concepts and enhance your practical skills.
<img align='center' src ='mines.png'>

## Table of Contents : 
### [Trajectory Clustering for Dumpers]()
-  [Objectives](#obj)
-  [Data Description](#desc)
-  [Deliverables](#devrilables)
-  [Tools and Resources](#tools)
  

### [General Guidelines]()
### [Assessment Criteria]()



### 1. Objectives : 
The primary objective of this project is to apply the concepts and techniques you've learned in the Advanced Machine Learning courses to real-world data, and this involves : 
  - **Data Cleaning and Preprocessing** ( Understand the structure of raw telematics data. Handle missing or noisy data and format the dataset for further analysis. This may involve techniques such as interpolation, outlier detection, and scaling.
Split the data into meaningful segments based on vehicle trajectories. )
  - **Exploratory Data Analysis (EDA)** Perform a comprehensive analysis of the dataset to uncover underlying patterns or characteristics (e.g., common trajectories, driving behaviors). Visualize data distributions and relationships, such as speed vs. time, acceleration profiles, or geographical movements.
  - **Distance Metrics for Trajectories** Learn and apply suitable distance measures for trajectories. These may include Euclidean distance, Dynamic Time Warping (DTW), or Fréchet distance. Experiment with different metrics to find the most suitable one for clustering vehicle trajectories.
  - **Trajectory Construction** ( Based on the preprocessed data, construct trajectories that reflect the vehicle's movement over time. Define how you will represent a trajectory (e.g., as a series of time-stamped GPS coordinates or motion states).
  - **Clustering Models Implementation** Apply different clustering algorithms (e.g., K-means, DBSCAN, Hierarchical Clustering ... ) to group similar trajectories. Compare how each clustering algorithm performs in terms of separating meaningful patterns in the data.
  - **Cluster Analysis and Comparison** Analyze and interpret the clustering results. Are the clusters meaningful? How do they reflect different types of driving behaviors or vehicle usage patterns? Compare clustering results using performance metrics such as silhouette score, Davies-Bouldin index, or visual inspection.


### 2. Data Description
The dataset you'll be working with consists of telematics data stored in a Parquet file. This dataset is collected from sensors and represents a multivariate time series, capturing various parameters that describe the vehicle's movement and driving behavior over time

### 3. Deliverables
- *Jupyter Notebook*:

A comprehensive notebook that includes all data preprocessing steps, exploratory data analysis (EDA), trajectory construction, distance metrics, clustering models, and result interpretation.
The notebook should be well-documented with explanations, code comments, and visualizations to clearly present your analysis.

- *Presentation*:

A concise presentation summarizing your approach, key findings, and insights derived from the data.
The presentation should highlight the main challenges faced, the solutions implemented, and the interpretation of the clustering results.
Use visuals and charts to effectively communicate your results and conclusions.
