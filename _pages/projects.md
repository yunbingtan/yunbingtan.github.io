---
layout: archive
permalink: /projects/
title: "Projects"
author_profile: true
redirect_from: 
  - /projects
---

{% include base_path %}

## Topic modeling with different corpora: Latent Dirichlet Allocation

* The model was set up under Dataproc from Google Cloud Platform (GCP). The <a href='https://spark.apache.org/docs/latest/api/python/reference/api/pyspark.ml.clustering.LDA.html'>LDA</a> library has already been established in PySpark. The library was used directly and some hyperparameters will be explored.
* An open-source data (<a href='https://www.gutenberg.org/'>Project Gutenberg</a>) was used. The size of the data is ~1 GB for this demo test. 
  * Data file upload to GCP.
  * Data preprocessing: such as text tokenization, stop word removal; 
  * Different inference methods: online variational Bayes vs expectation maximization; 
  * Data visualization using T-SNE
<br />
<img src="/images/project_1_1.png" alt="project1"><br />
Fig 1. Diagram of Spark components that are used in this project.

## Visual analytic systems to explore traffic patterns (VAST challenge 2017 MC1)

* Analyzed the dataset using Python and Tableau.
* Developed full-stack systems to present findings and support our hypotheses.
* Built coordinated visualizations with responsive front-end components by d3.js and HTML, and back-end components by Python and SQL.

### Overview 
<br />
<img src="/images/vas.png" alt="project2" width="600"><br />

### Architecture
- A compact database system that allows data retrieval using SQL syntax.

- Python functions to simplify data processing tasks and facilitate chart creation

- Four user interactive components:
  * A timeline chart that allows users to select a specific time range. As users adjust the timeline, other charts in the system update dynamically to reflect the chosen time interval.
  * A density map that allows users to select a range in the map. As selected, other charts in the system update dynamically to reflect the chosen location range.
  * A series of checkboxes that enable users to filter and find the data they need.
  * A tooltip function that allows users to check the value of each fraction of the pie charts

<br />
<img src="/images/project_2_1.png" alt="project2" width="600"><br />

## Convey's Game of Life iOS app

The Convey's Game of Life was developed as an iOS app for iPhone 15 and iPad Pro using Swift.
- The design architecture uses Model–view–viewmodel via ComposableArchitecture package.
- Three tag views were created as simulation, configuration, and statistics.
- Phase animations were added in the simulation and configuration views.

### Overview 
<p float="left">
  <img src="/images/Simulationview.png" alt="project2" width="200">
  <img src="/images/Configuration.png" alt="project2" width="200">
  <img src="/images/Statistics.png" alt="project2" width="200">
</p>

### Animation

<video width="320" height="240" controls>
  <source src="/images/Animation.mov" type="video/mp4">
</video>

## Sentiment analysis and digit recognition

* Feature engineering using variance threshold, recursive feature elimination, and principle component analysis.
*	Hyperparameter training: activation function (kernel function), hidden_layer, regularization, etc.
*	Model comparison: logistic regression, neural network, and support vector machines, AdaBoost.
