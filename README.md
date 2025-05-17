# 🎯 Data Preprocessing & K-Means Clustering

This project demonstrates a comprehensive approach to data preprocessing and the application of the K-Means clustering algorithm using Python. It encompasses data cleaning, feature engineering, normalization, and clustering techniques, providing insights into unsupervised learning methodologies.

## 📁 Repository Contents

* **`k-means model.ipynb`**: A Jupyter Notebook detailing the implementation of the K-Means clustering algorithm, including data preprocessing steps and visualization of clustering results.
* **`task 1 & 2 & 3.ipynb`**: Notebook covering initial data exploration, preprocessing tasks, and preliminary clustering experiments.
* **`movies(raw).csv`**: The original dataset containing raw movie data used for analysis.
* **`movies.csv`**: A cleaned and preprocessed version of the movie dataset, ready for clustering.
* **`numeric_dataset.csv`**: A numerically encoded dataset derived from the original data, suitable for machine learning algorithms.

## 🔍 Project Overview

The primary objective of this project is to cluster movies based on various features to uncover underlying patterns and groupings. The process involves:

1. **Data Cleaning**: Handling missing values, correcting data types, and removing inconsistencies.
2. **Feature Engineering**: Transforming categorical variables into numerical formats and creating new relevant features.
3. **Normalization**: Scaling features to ensure equal contribution to the clustering process.
4. **K-Means Clustering**: Applying the K-Means algorithm to segment movies into distinct clusters based on feature similarity.

## 🛠️ Technologies & Libraries

* **Programming Language**: Python 3.x
* **Libraries**:

  * `pandas`
  * `numpy`
  * `matplotlib`
  * `seaborn`
  * `scikit-learn`

## 📊 Methodology

1. **Data Exploration**: Initial analysis to understand data distribution, identify missing values, and detect outliers.
2. **Preprocessing**:

   * Imputation of missing values using appropriate strategies.
   * Encoding categorical variables using techniques like One-Hot Encoding.
   * Feature scaling using StandardScaler to normalize data.
3. **Clustering**:

   * Determining the optimal number of clusters (K) using the Elbow Method.
   * Applying the K-Means algorithm with the chosen K.
   * Visualizing clusters in two-dimensional space using PCA for dimensionality reduction.


## 🚀 Getting Started

To replicate this project:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Mariam7704/data-preprocessing-kmeans.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd data-preprocessing-kmeans
   ```

3. **Install required libraries**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Open Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

5. **Run the notebooks**: Open and execute the cells in `k-means model.ipynb` and `task 1 & 2 & 3.ipynb` sequentially.
