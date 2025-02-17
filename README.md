# Customer Segmentation Using K-means Clustering

## Project Overview

This project focuses on customer segmentation using K-means clustering, a popular unsupervised machine learning technique. By analyzing customer data from a mall, the project aims to group customers into distinct segments based on their annual income and spending score. This segmentation helps businesses understand customer behavior, allowing for targeted marketing strategies and improved customer satisfaction.

![1](https://github.com/PranayBhatnagar/Customer-Segmentation/assets/108617140/3a223493-0cbe-4b9d-b577-2dcb9e3eb2e3)

![2](https://github.com/PranayBhatnagar/Customer-Segmentation/assets/108617140/1ad6260e-9c85-4a14-9182-49aaf28b8ee0)

## Dataset

The dataset used for this project is sourced from Kaggle: [Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).

## Project Structure

- `customer_segmentation.ipynb`: Jupyter notebook containing the complete code and analysis.
- `customer_segmentation.py`: Complete code in Python language.
- `dataset/Mall_Customers.csv`: Entire dataset for the project.
- `README.md`: Project overview and documentation (this file).

## Dependencies

Ensure you have the following Python libraries installed:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install these dependencies using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Objective

The objective of this project is to perform customer segmentation using K-means clustering. The goal is to identify distinct groups of customers based on their annual income and spending score.

## Data Preprocessing

1. **Loading Data**: The dataset is loaded into a Pandas DataFrame.
2. **Initial Exploration**: The first few rows of the dataset are displayed, and the dataset's shape and information are checked.
3. **Missing Values Check**: The dataset is checked for any missing values.

## K-means Clustering

1. **Feature Selection**: The `Annual Income` and `Spending Score` columns are selected for clustering.
2. **Determining Optimal Clusters**: The Within Clusters Sum of Squares (WCSS) method is used to find the optimal number of clusters. An elbow plot is generated to visualize the optimal number.
3. **Model Training**: The K-means clustering model is trained with the optimal number of clusters.
4. **Cluster Labels**: Labels are assigned to each data point based on their cluster.
5. **Visualization**: The clusters and their centroids are visualized using scatter plots.

## Visualizations

The project includes visualizations to help understand the clustering process and the resulting customer segments. Key visualizations include:
- Elbow plot to determine the optimal number of clusters.
- Scatter plots to visualize the customer groups and their centroids.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/YourUsername/Customer-Segmentation.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Customer-Segmentation
    ```
3. Ensure all dependencies are installed:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Jupyter notebook to see the analysis:
    ```bash
    jupyter notebook customer_segmentation.ipynb
    ```

## Results

The K-means clustering algorithm segments the customers into 5 distinct clusters based on their annual income and spending score. Each cluster represents a different group of customers with similar behaviors, providing valuable insights for targeted marketing strategies.

## Future Work

Future improvements for this project could include:
- Incorporating additional features for clustering to enhance segmentation.
- Exploring other clustering algorithms for comparison.
- Deploying the model as a web application for interactive customer segmentation.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.
