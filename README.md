# Statistics-Review-Part-1
Unit 2 : Working with Data | Lesson 1 : Statistics Review

**Notebook:** [Statistics-Review-part-1.ipynb](./Statistics-Review-part-1.ipynb)
**Solutions:** [Statistics-Review-part-1-solution.ipynb](./solutions-code/Statistics-Review-part-1-solution.ipynb)


**Datasets:** [Titanic Survivors (CSV)](./data/titanic.csv) - Titanic passenger and survival information. This is a popular teaching dataset, e.g. on Kaggle.


### Learning Objectives
- **Compute** dot products, matrix multiplications, and vector norms by hand and using NumPy.
- **Code** summary statistics using NumPy and Pandas: mean, median, mode, max, min, quartile, inter-quartile range, variance, standard deviation, and correlation.
- **Create** basic data visualizations - including: scatter plots, box plots, and histograms.
- **Describe** characteristics and trends in a dataset using visualizations.
- **Describe** the bias and variance of statistical estimators.
- **Identify** a normal distribution within a dataset using summary statistics and data visualizations.


### Lesson Guide
- [Where are we in the data science workflow?](#where-are-we-in-the-data-science-workflow)
- [Linear Algebra Review](#linear-algebra-review)
    - [Scalars, vectors and matrices](#scalars-vectors-and-matrices)
	- [Basic matrix algebra](#basic-matrix-algebra)
	- [Dot product](#dot-product)
	- [Matrix multiplication](#matrix-multiplication)
	- [N-Dimensional space](#n-dimensional-space)
	- [Vector norm](#vector-norm)
- [Linear Algebra Applications to Machine Learning](#linear-algebra-applications-to-machine-learning)
	- [Distance between actual values and predicted values](#distance-between-actual-values-and-predicted-values)
	- [Mean Squared Error](#mean-squared-error)
	- [Least squares](#least-squares)
- [Codealong: Examining the Titanic Dataset](#codealong-examining-the-titanic-dataset)
- [Descriptive Statistics Fundamentals](#descriptive-statistics-fundamentals)
	- [Measures of Central Tendency](#measures-of-central-tendency)
	- [Math Review](#math-review)
	- [Measures of Dispersion: Standard Deviation and Variance](#measures-of-dispersion-standard-deviation-and-variance)
- [Our First Model](#our-first-model)
- [A Short Introduction to Model Bias and Variance](#a-short-introduction-to-model-bias-and-variance)
	- [Bias-Variance decomposition](#bias-variance-decomposition)
	- [Example using Bessel's correction](#example-using-bessels-correction)
- [Correlation and Association](#correlation-and-association)
	- [Codealong: Correlation in Pandas](#codealong-correlation-in-pandas)
- [The Normal Distribution](#the-normal-distribution)
	- [What is the Normal Distribution?](#what-is-the-normal-distribution)
	- [Skewness](#skewness)
	- [Kurtosis](#kurtosis)
- [Determining the Distribution of Your Data](#determining-the-distribution-of-your-data)
	- [Exercise](#exercise)
- [Topic Review](#topic-review)
