# K-Nearest Neighbors (KNN) Algorithm for Breast Cancer Classification


This project focuses on classifying breast cancer tumors as benign or malignant using the K-Nearest Neighbors (KNN) algorithm. The dataset used for training and testing is available [here](https://github.com/shawrajdeep00/K-nearest-neighbour/blob/main/Breast-Cancer.csv).


## Overview

- The code serves as an implementation of the k-Nearest Neighbors (KNN) algorithm, a versatile classification method.
- The initial dataset is structured to include two distinct groups, denoted as 'k' and 'r,' with associated two-dimensional data points.
- A new data point (`new_features`) is introduced for classification within this algorithmic framework.
- The computation of distances between the new point and existing data points is facilitated by both direct calculation and leveraging NumPy's linear algebra class.
- Distances, coupled with their corresponding groups, are systematically stored in the `distances` list.

## Core KNN Algorithm

- The KNN algorithm progresses by identifying the k-nearest neighbors, achieved by sorting distances and selecting the first k elements.
- Votes are assigned for each group among the identified neighbors, culminating in the determination of the predicted classification for the new point.

## Reusable Functionality

- Recognizing the importance of reusability, a function named `knn` is defined to encapsulate the KNN process, providing flexibility for deployment with diverse datasets.
- The functionality of the algorithm is showcased through its application to the predefined dataset and a new point, with the outcome elegantly displayed.

## Visualization

- The Matplotlib library is enlisted to create a scatter plot, offering a visual representation of the dataset and the new point.
- The resulting graph contributes to a better understanding of the spatial arrangement and distribution of data points.

## Application to Breast Cancer Dataset

- The algorithm's adaptability is underscored through its application to a breast cancer dataset.
- Pandas is harnessed for the reading of a CSV file, addressing missing values by replacing '?' with -99999, and performing requisite data preprocessing.
- Employing a train-test-split approach, the dataset is bifurcated into training and testing sets, with the random shuffling of data ensuring a balanced distribution.

## Accuracy Evaluation

- The accuracy of the KNN algorithm is systematically assessed for varying values of k.
- The outcomes of these evaluations are judiciously recorded in a list named `accuracy`.
- A graphical representation is generated, illuminating the nuanced relationship between k values and the corresponding accuracy metrics.

## Resultant Insights

- The final output is both informative and actionable, providing the maximum accuracy attained and the associated optimal k value.
- A graph visually interrogates the KNN algorithm's performance, thereby offering invaluable insights into its efficacy on the breast cancer classification problem.

## Conclusion

- The code's multifaceted functionality encompasses dataset manipulation, KNN implementation, visualization, and an in-depth evaluation on a breast cancer dataset.
- It serves as a comprehensive illustration of the algorithm's adaptability and nuanced performance across diverse scenarios.

Please refer to the .pynb file to see the visualized data, training mode, tested accuracy. Collaraborators are invited to make changes.
