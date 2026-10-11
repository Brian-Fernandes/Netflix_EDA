# Netflix EDA — Content Analysis and Clustering

## Project Overview

This project analyses the Netflix Movies and TV Shows dataset using Exploratory Data Analysis (EDA), statistical hypothesis testing, feature engineering, and unsupervised machine learning.

The objective is to identify patterns in the Netflix catalogue and investigate whether movies and TV shows can be grouped into meaningful clusters using their genres and textual descriptions.

## Objectives

- Explore the characteristics and distribution of Netflix titles.
- Investigate relationships between selected catalogue attributes using statistical tests.
- Transform genre and description data into numerical features.
- Apply and compare multiple clustering algorithms.
- Interpret cluster contents and identify a suitable model for content-based grouping.

## Methodology

1. Data loading and cleaning
2. Univariate, bivariate, and multivariate exploratory analysis
3. Statistical hypothesis testing
4. Genre encoding and TF-IDF feature extraction
5. Dimensionality reduction using TruncatedSVD
6. Clustering using MiniBatch K-Means, Bisecting K-Means, Agglomerative Clustering, and DBSCAN
7. Model evaluation and cluster interpretation

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset

The project uses the Netflix Movies and TV Shows dataset.

**Dataset source:** Add the original dataset URL here.

If the dataset is not included in this repository, download it from the source above and place the CSV in the `data/` directory before running the notebook.

## Main Findings

The project compares four clustering algorithms using internal evaluation metrics and examines their resulting cluster contents.

MiniBatch K-Means was selected as the preferred model in the standardised comparison because it performed best among the three fixed-cluster-count methods on the selected internal metrics and produced interpretable content groups.

The results are exploratory. The dataset does not contain individual user-interaction histories, so this project does not evaluate personalised recommendations or predict viewing behaviour.

## How to Run

1. Clone or download this repository.
2. Install the required Python packages.
3. Obtain the dataset and place it in the expected location.
4. Open `netflix_eda.ipynb` in Jupyter Notebook or Visual Studio Code.
5. Run the notebook cells in order.

## Limitations

- Clusters are not perfectly separated.
- Internal clustering metrics do not establish real-world recommendation quality.
- The results depend on the feature representation, sample, and algorithm parameters.

## Author

Add your name and relevant profile links here.
