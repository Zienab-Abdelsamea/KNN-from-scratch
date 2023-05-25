## K-Nearest Neighbors (KNN) on Iris Dataset

This repository contains an implementation of the K-Nearest Neighbors (KNN) algorithm from scratch using Python. The algorithm is applied to the famous Iris dataset for classification purposes.

### Dataset

The Iris dataset is a widely used benchmark dataset in machine learning. It consists of 150 samples of iris flowers, each described by four features: sepal length, sepal width, petal length, and petal width. The flowers belong to three different species: setosa, versicolor, and virginica.

The dataset is included in the repository as `iris.csv`. It is loaded and preprocessed before applying the KNN algorithm.

### Implementation

The KNN algorithm is implemented from scratch using Python and its scientific libraries, such as NumPy and Pandas. The implementation follows these main steps:

1. Load the dataset and preprocess it, including feature scaling and splitting into training and testing sets.
2. Define the KNN algorithm, which involves calculating the Euclidean distance between data points, finding the K nearest neighbors, and assigning the class label based on majority voting.
3. Evaluate the performance of the KNN algorithm using accuracy.

### Results

The accuracy achieved by the KNN algorithm on the Iris dataset is approximately 97%. This demonstrates the effectiveness of the algorithm in classifying the iris flowers based on their features.
### Author

This project was implemented by Zienab Abdelsamea. If you have any questions or suggestions, please feel free to reach out.

Enjoy exploring KNN on the Iris dataset!
