Introduction to data science using fisher's iris data and scikit-learn

# Steps to get started

1. Open on [Google Colab](https://colab.research.google.com/) and open the notebook using the [repository link](https://github.com/Data-and-Design-Lab/DS-Iris-Flower-dataset)
  1. If you do not see a dialog then, select File > Open Notebook
  2. Select "Github" > Enter Repository link > press enter
[https://github.com/Data-and-Design-Lab/DS-Iris-Flower-dataset](https://github.com/Data-and-Design-Lab/DS-Iris-Flower-dataset)
  3. select the notebook to get started
2. Explore the notebook

Or

1. Git clone the [repository](https://github.com/Data-and-Design-Lab/DS-Iris-Flower-dataset) to your machine
2. Install required packages (see tools section)
3. Explore the notebook

# Introduction

Iris is a beautiful flower but there are 260-300 species ([wikipedia](https://en.wikipedia.org/wiki/Iris_(plant))). We want to create an application that will observe features of the flower and tell us what species it is.

![](https://miro.medium.com/max/1400/1*uo6VfVH87jRjMZWVdwq3Vw.png)


Fig. 3 species in the Iris dataset ([source](https://medium.com/@Nivitus./iris-flower-classification-machine-learning-d4e337140fa4))

We will be working with the Iris Flower dataset also known as Fisher&#39;s Iris dataset. [Ronald Fisher](https://en.wikipedia.org/wiki/Ronald_Fisher) (1890 – 1962), a British statistician and biologist, introduced this multivariate data in his 1936 paper ([Fisher, 1936](https://onlinelibrary.wiley.com/doi/pdf/10.1111/j.1469-1809.1936.tb02137.x)). He used this data to show how linear discriminant analysis can be applied for taxonomy problems (see more in [Wikipedia](https://en.wikipedia.org/wiki/Iris_flower_data_set)). In machine learning textbooks, this dataset is used to introduce different concepts. Similarly, we will use this dataset to train a classification model. This dataset contains 5 columns and 150 rows of 3 species of Iris flower (preview in [UCI ML repository](https://archive.ics.uci.edu/ml/datasets/iris)). The columns are:

- Sepal length: Number / cm
- Sepal width: Number / cm
- Petal length: Number / cm
- Petal width: Number / cm
- Species: Text / &quot;Versicolor&quot;, &quot;Setosa&quot; or &quot;Virginica&quot;

| **row** | **sepal length (cm)** | **sepal width (cm)** | **petal length (cm)** | **petal width (cm)** | **species** |
| --- | --- | --- | --- | --- | --- |
| 0 | 5.1 | 3.5 | 1.4 | 0.2 | setosa |
| 1 | 4.9 | 3 | 1.4 | 0.2 | setosa |
| 2 | 4.7 | 3.2 | 1.3 | 0.2 | setosa |
| 3 | 4.6 | 3.1 | 1.5 | 0.2 | setosa |
| 4 | 5 | 3.6 | 1.4 | 0.2 | setosa |
| ... | ... | ... | ... | ... | ... |
| 145 | 6.7 | 3 | 5.2 | 2.3 | virginica |
| 146 | 6.3 | 2.5 | 5 | 1.9 | virginica |
| 147 | 6.5 | 3 | 5.2 | 2 | virginica |
| 148 | 6.2 | 3.4 | 5.4 | 2.3 | virginica |
| 149 | 5.9 | 3 | 5.1 | 1.8 | virginica |

To be able to differentiate and classify, we will be doing the following analyses using Data Science and Machine Learning tools.

# Analysis

Descriptive

- Simple statistics: mean, standard deviation, median, etc.
- Visualization
- Clustering with [k-means](https://en.wikipedia.org/wiki/K-means_clustering)

Predictive

- Classification models: Artificial Neural network (Multi-Layer Perceptron), Support Vector Machines (SVM), Decision tree and Random Forest
- Model evaluation using confusion matrix

# Tools for analysis

We will be using the following Python (v3.7) packages:

1. [pandas](https://pandas.pydata.org/docs/index.html) for data analysis
2. [sklearn](https://scikit-learn.org/stable/index.html) (scikit-learn) for training models
3. [Seaborn](https://seaborn.pydata.org/index.html) for visualization
4. [Yellowbrick](https://www.scikit-yb.org/en/latest/index.html) for ML visualization

# Exercise

Create a presentation containing slides on (total 4 slides) in 45 minutes

- What is the problem
- Challenges
- Key findings
- Model accuracy
