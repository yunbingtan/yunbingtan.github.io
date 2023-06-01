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
* The model was set up under Dataproc from google cloud platform (GCP). The <a href='https://spark.apache.org/docs/latest/api/python/reference/api/pyspark.ml.clustering.LDA.html'>LDA</a> library has already been established in PySpark. The library was used directly and some hyperparameters will be explored.
* An open-source data (<a href='https://www.gutenberg.org/'>Project Gutenberg</a>) was used. The size of the data is ~1 GB for this demo test. 
  * Data file upload to GCP.
  * Data preprocessing: such as text tokenization, stop word removal; 
  * Different inference methods: online variational Bayes vs expectation maximization; 
  * Data visualization using T-SNE
<br />
<img src="/images/project_1_1.png" alt="project1"><br />
Fig 1. Diagram of Spark components that are used in this project.

## Visual analytics systems to explore traffic pattern (VAST Challenge 2017 MC1)
* Analyzed the dataset using python and tableau.
* Developed full-stack systems using to present findings and suppourt our hypotheses.
* Built coordinated visualizations with responsive front-end components by d3.js and HTML, and back-end by Python and SQL.
<br />
<img src="/images/project_2_1.png" alt="project2" width="600"><br />
Fig 2. Architecture of visual analytic systems.

## Sentiment analysis and digit recognition
* feature engineering using variance threshold, recursive feature elimination, principle component analysis.
*	Hyperparameter training: activation function (kernal function), hidden_layer, regularization etc.
*	Model comparison: logistic regression, neural network, and support vector machines, AdaBoost.
