---
title: Projects
layout: default
---

# Data Science Projects

Below is a selection of projects I've worked on that showcase my skills and experience in data science:

## [NLP Analysis of Medical Questions](https://github.com/petertadrous/medical-questions-processing)

- Analyzed structured text data from 23,000+ patient questions from 12 NIH sites with NLTK and Scikit-Learn
- Reduced features with PCA and t-SNE, clustered with K-Means and DBSCAN, modeled topics with LDA
- Found 3 topics of questions for Symptoms, Visits, and Disorders with potential for more granular subtopics

## [Bayesian Dropout Layer in FairFace Network](https://github.com/petertadrous/cus754-capstone)

- Analyzed the addition of a Bayesian Dropout Layer to a pre-trained ResNet34 model for face recognition (FairFace)
- Converted the model weights and biases from a PyTorch neural network to Keras to leverage transfer learning
- Found that Bayesian dropout resulted in lower accuracy vs. both a traditional dropout layer and the original model

## Clustering Analysis of Disease Outbreaks

- Extracted disease and location data from unstructured text data of 650 news headlines with GeoNamesCache
- Clustered with DBSCAN using implementation of Great Circle Distance to account for earth's curvature
- Identified 3 potential budding pandemics by analyzing prevalence of diseases in 11 clusters

## [Automated Stock Trading System](https://github.com/petertadrous/automated-trading)

- Implemented object-oriented stock trader that simulated buying and selling stocks in a portfolio based on short- and long-rolling-averages in financial time series data
- Leveraged multiprocessing parallelization for efficiency
- Resulted in measurably higher returns than a traditional strategy of buying high and selling low

## Statistical Modeling to Identify Factors of Obesity in the US

- Analyzed data from the 50 States and D.C. using linear regression to explain the variation in obesity rate
- Visualized findings with histograms and scatterplots using the statistical program SPSS

[Return to Home](index.md)
