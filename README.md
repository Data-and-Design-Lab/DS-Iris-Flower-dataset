# Introduction to data science using fisher's iris data and scikit-learn

## Introduction

### Dataset

We will be working with the Iris Flower dataset also known as Fisher&#39;s Iris dataset. Fisher introduced this multivariate data in his 1936 paper ([Fisher, 1936](https://onlinelibrary.wiley.com/doi/pdf/10.1111/j.1469-1809.1936.tb02137.x)). He used this data to show how linear discriminant analysis can be applied for taxonomy problems (see more in [Wikipedia](https://en.wikipedia.org/wiki/Iris_flower_data_set)). In machine learning, this dataset is used to introduce different concepts in textbooks. Similarly, we will use this dataset to train a classification model.

This dataset contains 5 columns and 150 rows. The columns are:

- Sepal length: Number / cm
- Sepal width: Number / cm
- Petal length: Number / cm
- Petal width: Number / cm
- Species: Text / &quot;Versicolor&quot;, &quot;Setosa&quot; or &quot;Virginica&quot;

### Python packages

We will use the following packages:

1. [pandas](https://pandas.pydata.org/docs/index.html) for data analysis
2. [sklearn](https://scikit-learn.org/stable/index.html) (scikit-learn) for training models
3. [Seaborn](https://seaborn.pydata.org/index.html) for visualization
4. [Yellowbrick](https://www.scikit-yb.org/en/latest/index.html) for ML visualization

## Analysis

Descriptive

- Simple statistics: mean, standard deviation, median, etc.
- Visualization
- Clustering with [k-means](https://en.wikipedia.org/wiki/K-means_clustering)

Predictive

- Classification models: MLP/ANN, SVM, Decision tree, random forest
- model evaluation using confusion matrix

## Output

Create a presentation containing slides on

- what is the problem
- challenge
- key findings
- accuracy
