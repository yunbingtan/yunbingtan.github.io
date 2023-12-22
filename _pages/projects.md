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
------

* The model was set up in Dataproc from Google Cloud Platform (GCP).
* Established in PySpark, the <a href='https://spark.apache.org/docs/latest/api/python/reference/api/pyspark.ml.clustering.LDA.html'>LDA</a> library was used directly for data analysis.
* An open-source data (<a href='https://www.gutenberg.org/'>Project Gutenberg</a>) was used. The size of the data is ~1 GB for this demo test. 
  * Data files uploaded to GCP.
  * Data preprocessing: such as text tokenization, stop word removal.
  * Different inference methods for LDA: online variational Bayes vs expectation maximization.
  * Data visualization using T-SNE.
<br />
<img src="/images/project_1_1.png" alt="project1"><br />

## Visual analytic systems to explore traffic patterns (VAST challenge 2017 MC1)
------

* Analyzed the dataset using Python and Tableau.
* Developed full-stack systems to present findings and support our hypotheses.
* Built coordinated visualizations with responsive front-end components by d3.js and HTML, and back-end components by Python and SQL.

### Overview 
<img src="/images/vas.png" alt="project2" width="600"><br />

### Architecture
* A compact database system that allows data retrieval using SQL syntax.
* Python that simplifies data processing and connects the backend and the front_end.
* Four user interactive components:
  * A timeline chart that allows users to select a specific time range. As users adjust the timeline, other charts update dynamically to reflect the chosen time interval.
  * A density map that allows users to select a range in the map. As selected, other charts in the system update dynamically to reflect the chosen location range.
  * A series of checkboxes that enable users to filter and analyze the data.
  * A tooltip function that allows users to view the value of each fraction of the pie charts.

<img src="/images/project_2_1.png" alt="project2" width="600"><br />

## Convey's Game of Life iOS app
------

The Convey's Game of Life was developed as an iOS app for iPhone 15 and iPad Pro using Swift.
- The design architecture used Model–view–viewmodel via ComposableArchitecture package.
- Three tag views were created as simulation, configuration, and statistics.
- Phase animations were added in the simulation and configuration views.

### Overview 
<p float="left">
  <img src="/images/Simulationview.png" alt="project2" width="200">
  <img src="/images/Configuration.png" alt="project2" width="200">
  <img src="/images/Statistics.png" alt="project2" width="200">
</p>

### Animation
<br />
<video width="320" height="240" controls>
  <source src="/images/Animation.mov" type="video/mp4">
</video>

## Sentiment analysis and digit recognition
------

* Performed feature engineering using variance threshold, recursive feature elimination, and principle component analysis.
*	Trained hyperparameters via different activation functions (kernel function), number of hidden_layer, regularization parameters, etc.
*	Compared different models such as logistic regression, neural network, and support vector machines, AdaBoost.
