 **ASSIGNMENT_KNN - K-means Clustering *

-----------------------------------------------------------------------------------------------------------------------------------------------------------

**NAME : SAYANTAN CHAUDHURI**

**ROLL NO.: 2206211**

**SECTION : IT01**

-----------------------------------------------------------------------------------------------------------------------------------------------------------
> **QUESTION**
In this assignment, you need to implement the K-means clustering
algorithm on the following dataset.

> Dataset - `kmeans - kmeans_blobs.csv`

> What to Submit?
1. You need a submit a single PDF report file and the name of
that file should be your roll numbers.
2. You need to run the k-means algorithm on the dataset for k=2,
k=3.
3. In your report, you should have 2 plots - one for k = 2 and
the other for k = 3. In the plot, you need to plot the given
dataset and use different colors to show points belonging to a
particular cluster. Example,

> Note
1. Your code should be in Python.
2. You are not allowed to use libraries like sci-kit learn, Tensorflow,
Pytorch, etc, and use their built-in linear regression models.
3. You may use libraries like numpy, pandas, matplotlib, etc to read
and manipulate the dataset and plot the graphs.
4. Your plots should be labeled properly.
5. Normalize your predictor before starting training the model.

----------------------------------------------------------------------------------------------------------------------------------------------------------------

## Steps
1. **Load & Normalize Data** - Reads the dataset and scales it between 0 and 1.
2. **Initialize Centroids** - Randomly selects `k` initial centroids.
3. **Assign Clusters** - Each point is assigned to the nearest centroid.
4. **Update Centroids** - Computes new centroids by averaging assigned points.
5. **Repeat Until Convergence** - Stops when centroid movement is minimal.
6. **Plot Results** - Generates scatter plots for `k=2` and `k=3` clustering.
