# Description

Time do to an end-to-end project in data science. which means:

Loading the dataset.
Summarizing the dataset.
Visualizing the dataset.
Evaluating some algorithms.
Making some predictions.
A must-see example of data science is the iris dataset. We will predict which class of iris plant a plant belongs to based on its characteristics.

# Task

Environment. We will use Jupyter.

In Data Science, the winning combo is pandas (and/or numpy), matplotlib, sklearn (and/or keras). In this project, we will use:

pandas to load the data
matplotlib to do the visualization
sklearn to do the prediction
Load dataset
url = "URL"
dataset = read_csv(url)
Summarizing the dataset
A - Printing dataset dimension

print(dataset.shape)
# should something like: (150, 5)
B - It is also always a good idea to eyeball your data.

print(dataset.head(20))
C - Statistical Summary The statistical summary includes the count, mean, the min and max values, and some percentiles.

print(dataset.describe())
D - Class Distribution Group by to see how our data are distributed.

print(dataset.groupby('class').size())

# Install & Usage
pip install pandas
pip install numpy

jupyter-notebook --no-browser