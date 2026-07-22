
# Iris Dataset Analysis

This notebook performs an exploratory data analysis on the famous Iris dataset.

## Steps:

1.  **Load Data**: The Iris dataset is loaded using `sklearn.datasets.load_iris`.
2.  **Data Preparation**:
    *   The dataset is converted into a Pandas DataFrame.
    *   The numerical species target is mapped to human-readable species names (`setosa`, `versicolor`, `virginica`).
3.  **Data Overview**: Basic information and the head of the DataFrame are displayed to understand its structure.
4.  **Data Visualization**: A pair plot is generated using `seaborn` to visualize the relationships between all pairs of features, colored by species, helping to identify separability and distributions.

## Libraries Used:

*   `sklearn` for dataset loading.
*   `pandas` for data manipulation.
*   `seaborn` and `matplotlib.pyplot` for data visualization.
