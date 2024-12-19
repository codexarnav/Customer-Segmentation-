# Customer Segmentation Analysis using K-means Clustering

## Overview
This project implements customer segmentation using K-means clustering algorithm to group customers based on their Annual Income and Spending Score. The analysis helps identify distinct customer segments, enabling targeted marketing strategies and better customer understanding.

## Dataset
The dataset contains customer information with the following features:
- Annual Income (k$)
- Spending Score (1-100)

## Project Structure
```
├── data/
│   └── customer_data.csv
├── notebooks/
│   └── customer_segmentation.ipynb
├── src/
│   ├── preprocessing.py
│   └── clustering.py
└── requirements.txt
```

## Key Features
- Data preprocessing and exploration
- Implementation of K-means clustering algorithm
- Determination of optimal number of clusters using elbow method
- Visualization of customer segments
- Analysis of cluster characteristics

## Technical Stack
- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn

## Installation
1. Clone the repository
```bash
git clone https://github.com/yourusername/customer-segmentation.git
cd customer-segmentation
```

2. Create and activate virtual environment (optional)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages
```bash
pip install -r requirements.txt
```

## Usage
1. Place your customer data in the `data` directory
2. Run the Jupyter notebook:
```bash
jupyter notebook notebooks/customer_segmentation.ipynb
```

## Results
The analysis identified distinct customer segments based on spending patterns and income levels:
- Cluster 1: High income, High spending
- Cluster 2: High income, Low spending
- Cluster 3: Average income, Average spending
- Cluster 4: Low income, High spending
- Cluster 5: Low income, Low spending

## Visualizations
The project includes several visualizations:
- Elbow curve for optimal k selection
- Scatter plot of customer segments
- Distribution plots for each feature
- Cluster centroid analysis


Dataset:https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
