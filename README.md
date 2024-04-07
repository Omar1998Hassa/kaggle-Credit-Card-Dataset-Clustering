# Credit Card Data Analysis and Clustering

## Overview

This repository contains an in-depth analysis of credit card transaction data using various clustering techniques and outlier detection methods. The analysis aims to uncover meaningful patterns and structures within the dataset, providing valuable insights into user behavior and transaction trends.

## Project Structure

The project is organized as follows:

- **Data**: This directory contains the raw credit card transaction data (`credit_card_data.csv`) used for the analysis.

- **Notebooks**: This directory contains Jupyter Notebooks detailing the analysis process step by step. Each notebook focuses on a specific aspect of the analysis, such as data preprocessing, clustering, and outlier detection.

- **Scripts**: This directory contains Python scripts that can be used to execute specific parts of the analysis programmatically.

- **Visualizations**: This directory contains visualizations generated during the analysis, including cluster plots, t-SNE visualizations, and outlier detection plots.

- **Results**: This directory contains summary files and reports generated from the analysis, including cluster descriptions, outlier statistics, and conclusions.

- **Requirements.txt**: This file lists all the Python dependencies required to run the analysis. These dependencies can be installed using `pip install -r requirements.txt`.

## Analysis Steps

1. **Data Preprocessing**: The raw credit card transaction data is preprocessed to handle missing values, scale features, and encode categorical variables. Exploratory data analysis (EDA) is performed to gain insights into the data distribution and identify any anomalies.

2. **Clustering Techniques**: Various clustering techniques, including K-means, Kernel K-means, Gaussian Mixture Model, and DBSCAN, are applied to the preprocessed data. Each technique is evaluated based on its ability to partition the data into meaningful clusters.

3. **Cluster Identification**: Each cluster is analyzed to understand its unique characteristics, such as purchase behavior, spending patterns, and engagement in cash advance transactions. Visualization techniques like t-SNE are used to visualize the clusters in a lower-dimensional space.

4. **Efficiency Comparison**: The efficiency of Principal Component Analysis (PCA) and Kernel PCA for clustering is compared. The analysis evaluates the performance of each method based on metrics such as silhouette score and misclassification rate.

5. **Hierarchical Clustering**: Hierarchical clustering is explored to understand the hierarchical structure of the data. The analysis examines the computational complexity and interpretability of hierarchical clustering compared to other clustering techniques.

6. **Outlier Detection**: Three outlier detection methods—Expectation Maximization, DBSCAN, and Isolation Forest—are applied to identify outliers in the dataset. The analysis evaluates the effectiveness of each method in detecting anomalies and provides insights into the characteristics of the outliers.

7. **Conclusion**: The analysis concludes with a summary of findings, highlighting key insights gained from the clustering and outlier detection process. Recommendations for further analysis or actions based on the insights are also provided.

## Usage

To replicate the analysis:

1. Clone this repository to your local machine.
2. Install the required dependencies listed in `requirements.txt` using `pip install -r requirements.txt`.
3. Navigate to the `Notebooks` directory and run the Jupyter Notebooks in sequential order to execute the analysis steps.
4. Alternatively, use the Python scripts provided in the `Scripts` directory to execute specific parts of the analysis programmatically.

## Contributors

- [Omar Yasser](https://github.com/Omar1998Hassa)


## Acknowledgments

Special thanks to [Kaggle](https://www.kaggle.com) for providing the credit card transaction data used in this analysis.
