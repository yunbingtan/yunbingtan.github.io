---
layout: archive
permalink: /projects/
title: "Projects"
author_profile: true
redirect_from: 
  - /projects
---

{% include base_path %}

## Topic Modeling with Different Corpora: Latent Dirichlet Allocation
* The model was set up under Dataproc from google cloud platform (GCP). The <a href='https://spark.apache.org/docs/latest/api/python/reference/api/pyspark.ml.clustering.LDA.html'>LDA</a> library has already been established in PySpark. The library was used directly and some hyperparameters will be explored.
* An open-source data (<a href='https://www.gutenberg.org/'>Project Gutenberg</a>) was used. The size of the data is ~1 GB for this demo test. 
  * Data file upload to GCP.
  * Data preprocessing: such as text tokenization, stop word removal; 
  * Different inference methods: online variational Bayes vs expectation maximization; 
  * Data visualization using T-SNE
