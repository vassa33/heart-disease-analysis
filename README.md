# Heart Disease Dataset Analysis

This repository contains a Jupyter notebook (`heart_disease_analysis.ipynb`) that performs an analysis of a heart disease dataset from the UCI Machine Learning Repository. 

## Dataset

The dataset includes 14 attributes such as:

- Age
- Sex
- Chest pain type
- Blood pressure
- Serum cholesterol
- Target variable indicating the presence or absence of heart disease

## Analysis

The analysis includes the following steps:

1. **Loading the Dataset**: The heart disease dataset is loaded into a pandas data frame.

2. **Exploratory Data Analysis (EDA)**: EDA is performed to gain insights into the dataset.

3. **Data Preprocessing**: The dataset is preprocessed by handling missing values, scaling the features, and encoding categorical variables.

4. **Clustering**: K-means clustering, hierarchical clustering, and DBSCAN clustering are applied to the preprocessed dataset to group patients into clusters based on their medical history.

5. **Visualization**: Principal component analysis (PCA) and t-SNE are used to visualize the clusters and gain insights into the relationships between the variables.

6. **Risk Factor Identification**: Gaussian mixture models (GMMs) are used to identify risk factors associated with heart disease.

7. **Clustering Performance Evaluation**: The clustering performance is evaluated using metrics such as silhouette score and Davies-Bouldin index.

8. **Clustering Algorithm Comparison**: The performance of different clustering algorithms is compared and the one that gives the best results is chosen.

The notebook is well-documented with comments and follows best practices. The code, data, and visualizations are included in the notebook.

## Requirements

To run the notebook, you need to have the following packages installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

You can install these packages using pip:

```
pip install -r requirements.txt
```

## Usage

To run the notebook, open it in Jupyter Notebook and run the cells sequentially.

```
jupyter notebook heart_disease_analysis.ipynb
```

## Colab

Link to [Colab Notebook](https://colab.research.google.com/drive/1V5ktHIVTTPiWVhnvoYl4V4EZOLhLXdKc?usp=sharing).

