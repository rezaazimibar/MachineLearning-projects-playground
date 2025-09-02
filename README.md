# Machine Learning Algorithms and Projects

This repository contains a collection of **Machine Learning algorithms** and several **end-to-end ML projects**, organized in separate folders for clarity and ease of navigation.

The goal of this repo is to provide both **implementations of core algorithms** from scratch or using libraries, and **complete pipelines** that cover data preprocessing, model training, evaluation, and visualization.

---

## 📂 Repository Structure

- **tool_box_projects/**  
  Contains implementations of different ML algorithms (e.g., SVM, Decision Trees, Logistic Regression, KNN, etc.).

- **end_to_end_projects/**  
  End-to-end ML projects that include dataset preparation, model training, hyperparameter tuning, evaluation, and results visualization.

Each folder has its own README (if needed) and code/scripts for better organization.

---

## 🤖 Implemented Algorithms

This repository contains implementations of several ML algorithms.  
Below you can find a short description and visualization for each one.

### 🔠 Classification models

---

#### 🔹 Logistic Regression Classifier

The **Logistic Regression Classifier** is a linear model for binary classification that uses the logistic (sigmoid) function to model the probability of a data point belonging to a particular class. It is widely used for tasks like predicting user purchases, with built-in support for regularization to prevent overfitting. This implementation includes data preprocessing, model fitting, evaluation metrics, and visualization of the classification results on a dataset of social network ads.

<p align="center">
  <img src="./tool_box_projects/02.Classification/01. logistic_regression/figure.png" width="50%">
</p>

---

#### 🔹 K-Nearest Neighbors (KNN) Classifier

The **K-Nearest Neighbors (KNN) Classifier** is a non-parametric, instance-based learning algorithm that classifies new data points based on the majority vote of their k closest neighbors in the feature space, using distance metrics like Euclidean. It is simple yet effective for classification tasks, especially with small datasets, and includes preprocessing, training, evaluation, and visualization of decision boundaries.

<p align="center">
  <img src="./tool_box_projects/02.Classification/02. K_nearest_neighbors/figure.png" width="50%">
</p>

---

#### 🔹 Support Vector Machine (SVM) Classifier

The **Support Vector Machine (SVM) Classifier** is a powerful supervised learning model that finds the optimal hyperplane to separate classes in the feature space, maximizing the margin between support vectors. It is effective for both linear and non-linear classification tasks through kernel tricks like RBF. This implementation covers data preprocessing, model training, evaluation, and visualization of the decision boundaries on a social network ads dataset.

<p align="center">
  <img src="./tool_box_projects/02.Classification/03. Support_vector_machine/figure.png" width="50%">
</p>

---

#### 🔹 Support Vector Machine (SVM) with RBF Kernel

The **SVM with RBF kernel** is capable of handling non-linear decision boundaries by mapping the input space into a higher-dimensional feature space.  
The visualization below shows how the RBF kernel separates two classes and adapts to complex data distributions.

<p align="center">
  <img src="./tool_box_projects/02.Classification/04.%20RFB_SVM/figure.png" width="50%">
</p>

---

#### 🔹 Naive Bayes Classifier

The **Naive Bayes classifier** is a probabilistic model based on Bayes’ theorem with the assumption of conditional independence between features.  
It is widely used in text classification, spam filtering, and sentiment analysis due to its simplicity and efficiency.

Below is an example output visualization from the notebook:

<p align="center">
  <img src="./tool_box_projects/02.Classification/05.%20Naive_bayes/figure.png" width="50%">
</p>

---

#### 🔹 Decision Tree Classifier

The **Decision Tree Classifier** implementation demonstrates how decision trees can be applied for supervised learning tasks. It covers dataset preprocessing, model training, and visualization of the decision boundaries, making it easier to interpret how the algorithm splits the feature space for classification.

<p align="center">
  <img src="./tool_box_projects/02.Classification/06.%20Decision_tree_classification/figure.png" width="50%">
</p>

---

#### 🔹 Random Forest Classifier

The **Random Forest Classifier** is an ensemble learning method that builds multiple decision trees and combines their predictions to improve accuracy and reduce overfitting. This implementation includes preprocessing, training, evaluation, and visualization of results, highlighting the robustness and reliability of random forests for classification tasks.

<p align="center">
  <img src="./tool_box_projects/02.Classification/07.%20Random_forest_classification/figure.png" width="50%">
</p>

---

### 🔠 Cluster models

---

#### 🔹 K-Means Clustering

The K-Means Clustering notebook applies unsupervised learning to segment customers from the Mall Customers dataset based on their annual income and spending score. The project begins with data preprocessing and exploratory visualizations to understand feature distributions. The Elbow Method is then used to identify the optimal number of clusters, followed by training a K-Means model. Finally, the resulting customer segments are visualized with clear separation of clusters and their centroids, providing insights into consumer behavior and spending patterns.

<p align="center">
  <img src="./tool_box_projects/03.Clustering/01.%20K_mean_cluster/figure.png" width="80%">
</p>

---

#### 🔹 Hierarchical Clustering  

The **Hierarchical Clustering** implementation showcases how data points can be grouped into clusters based on their similarity using agglomerative (bottom-up) techniques. This notebook covers dataset preprocessing, building dendrograms, applying clustering, and visualizing the hierarchical structure to better understand relationships between clusters.

<p align="center">
  <img src="./tool_box_projects/03.Clustering/02.%20Hierarchical_clustering/figure.png" width="80%">
</p>

---

### 🔠 Cluster models


#### 🔹 Apriori Algorithm  

The **Apriori Algorithm** is implemented to identify frequent itemsets and generate association rules from transactional datasets. This notebook demonstrates how to apply Apriori for market basket analysis, covering data preprocessing, rule generation, and visualization of item associations to uncover hidden patterns in data.

---

### 🔹 Eclat Algorithm  

The **Eclat Algorithm** is implemented for frequent itemset mining using a depth-first search approach based on set intersections. This notebook demonstrates how to apply Eclat for market basket analysis, focusing on discovering frequent item combinations efficiently and generating insights into hidden associations within the dataset.

---

## 🚀 Features

- Step-by-step implementations of popular ML algorithms.
- Clean and organized project structure.
- End-to-end pipelines covering the full ML workflow.
- Visualizations and plots for better understanding of results.

---

## 📊 Example Topics Covered

- Supervised Learning (Classification & Regression)
- Unsupervised Learning (Clustering, Dimensionality Reduction)
- Model Evaluation Metrics and Confusion Matrices
- Decision Boundaries Visualization

---

## 🤝 Contribution

Feel free to fork this repository, open issues, or submit pull requests if you’d like to add more algorithms, projects, or improvements.

---

## 📜 License

This repository is licensed under the MIT License. See the LICENSE file for more details.

<!-- ![Cluster Result](./tool_box_projects/03.Clustering/02.%20Hierarchical_clustering/figure.png) -->
