# Customer Segmentation Using K-Means Clustering

## Overview
This project applies K-Means clustering for customer segmentation based on their purchasing behavior. The dataset contains various attributes such as balance, purchase frequency, credit limit, and payment behavior. The goal is to identify distinct customer groups to optimize marketing strategies.

## Features
- Loads and cleans customer transaction data.
- Handles missing values in critical columns.
- Performs exploratory data analysis (EDA) with visualizations.
- Identifies correlations between key financial attributes.
- Implements K-Means clustering to segment customers.
- Determines the optimal number of clusters using the elbow method.
- Uses Principal Component Analysis (PCA) for dimensionality reduction and visualization.
- Explores Autoencoders for potential feature extraction.

## Requirements
Install the necessary dependencies using:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn tensorflow
```

## File Structure
- `Marketing_data.csv` - CSV file containing customer transaction data.
- `marketing_segmentation.ipynb` - Jupyter Notebook for data processing and clustering.

## How to Run
1. Ensure the `Marketing_data.csv` file is in the working directory.
2. Open the Jupyter Notebook and execute the cells step by step.
3. The notebook will generate visualizations and perform customer segmentation.

## Explanation of Key Steps
### Data Preprocessing
- Loads the dataset and inspects its structure.
- Handles missing values by filling them with column means.
- Removes unnecessary columns (e.g., Customer ID).
- Standardizes the dataset for clustering.

### Exploratory Data Analysis (EDA)
- Generates histograms and distribution plots for feature analysis.
- Creates correlation heatmaps to identify relationships between variables.
- Uses pair plots to visualize trends in purchasing behaviors.

### K-Means Clustering
- Determines the optimal number of clusters using the elbow method.
- Applies K-Means clustering to group customers based on their financial attributes.
- Analyzes the characteristics of each customer segment.

### Principal Component Analysis (PCA)
- Reduces data dimensions to visualize cluster separation.
- Uses a scatter plot to display clusters in a 2D space.

### Autoencoders (Experimental)
- Implements a neural network-based autoencoder for feature extraction.
- Uses TensorFlow/Keras to encode and decode customer data.

## Output
- Clustered customer groups based on transaction patterns.
- Insights into different customer types, such as transactors, revolvers, and VIPs.
- Visualizations for better understanding of data distribution and segmentation.

## License
This project is open-source and can be used for educational and research purposes.

