# Iris-Dataset Analysis
## Overview

This repository contains an analysis of the classic Iris flower dataset. The dataset includes 150 samples from each of three species of Iris flowers: Iris setosa, Iris virginica, and Iris versicolor. Each sample consists of four features: sepal length, sepal width, petal length, and petal width.

The goal of this project is to explore the dataset, perform data analysis, and create visualizations to gain insights into the features and species. Additionally, we apply machine learning techniques to classify the different species of Iris flowers.


## Dataset

The Iris dataset is one of the most well-known datasets in data science and is available in the sklearn library. It includes the following columns:


- Sepal Length (cm)

- Sepal Width (cm)

- Petal Length (cm)

- Petal Width (cm)

- Species (Iris-setosa, Iris-versicolor, Iris-virginica)


## Repository Contents

Iris_analysis.ipynb: The main Jupyter Notebook containing:

- Data loading and exploration

- Data visualization

- Machine learning classification models

- README.md: This file, providing an overview of the project.

## Insights:

 #### Matplotlib:
 
 Matplotlib is a comprehensive library for creatinhg static,animated,and interactive visualizations
 in Python.It is widely used for plotting data and offers flexibility and control over the appearance
 of plots.It provides a wide variety of plotting options including line plots, scatter plots, bar charts,
 histograms, and more.

 
 #### Seaborn:
 
 Seaborn is a Python data visualization library based on Matplotlib. It provides a high-level interface
 for creating informative and attractive statistical graphics. Seaborn simplifies the process of creating
 common visualization types and integrates well with Pandas data structures.
 

 PAIRPLOT : A pairplot is a great way to visualize relationships between all pairs of features in
 a dataset. It creates a matrix of scatter plots, where each scatter plot shows the relationship
 between two different features.The diagonal of the matrix shows the distribution of each feature
 using histograms or kernel density estimations.


 PIE CHART : A pie chart is a circular statistical graphic, which is divided into slices to illustrate
 numerical proportion. In a pie chart, the arc length of each slice (and consequently its central angle
 and area), is proportional to the quantity it represents. While it is named for its resemblance to a
 pie which has been sliced, there are variations on the way it can be presented.


 SCATTER PLOT : A scatter plot uses dots to represent values for two different numeric variables.
 The position of each dot on the horizontal and vertical axis indicates values for an individual data
 point. Scatter plots are used to observe relationships between variables.


 JOINT PLOT : Ajointplot is a way to visualize the relationship between two variables, along with their
 individual distributions. It combines a scatter plot with histograms or kernel density estimations
 to show both the bivariate and univariate distributions.
 

 KDE PLOT : Akdeplot (Kernel Density Estimation plot) is a way to visualize the distribution of a
 single variable or the relationship between two variables. It uses a kernel density estimate to show
 the probability density function of the data.
 KDE plots are especially useful for visualizing the shape of a distribution and identifying any
 clusters or outliers.

## Analysis Steps

1. Data Loading and Exploration:

   - Loaded the dataset and inspected the first few rows to understand its structure.

   - Summary statistics of the dataset were generated.

3. Data Visualization:

   - Plotted pairwise relationships between the features using scatter plots.

   - Created histograms for each feature to visualize the distribution.

   - Visualized the relationship between features and the species using box plots and violin plots.


3. Machine Learning Models:

   - Split the dataset into training and testing sets.

   - Applied several classification models, including:

     -- K-Nearest Neighbors (KNN)

     -- Support Vector Machine (SVM)

     -- Random Forest Classifier

   - Evaluated the models' performance based on accuracy, precision, recall, and F1-score.


## Libraries Used:

-pandas

-numpy

-matplotlib

-seaborn

-scikit-learn


## How to Run

1. Clone the repository:
 
   git clone https://github.com/VyshnaviVunnamatla/Iris-Dataset.git

2. nstall the required libraries:
  ```pip install -r requirements.txt```

3. Run the Jupyter notebook to explore the dataset and models:
  ```jupyter notebook Iris_analysis.ipynb```


## Conclusion

This analysis demonstrates how the Iris dataset can be used for a simple yet effective classification problem. The exploratory data analysis provides valuable insights into the relationships between features, while the machine learning models offer robust classification of the Iris species with high accuracy.
