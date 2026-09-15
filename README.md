# Customer Segmentation using K-Means

## Project Overview
This project performs customer segmentation using K-Means clustering on a marketing campaign dataset.

## Objective
The objective is to identify meaningful customer groups based on demographics, income, spending behavior, purchasing channels, and recency.

## Dataset
Marketing Campaign Dataset

- Original records: 2240
- Records after cleaning: 2216
- Missing Income values were removed.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Data Processing
The project includes:
- Data cleaning
- Feature engineering
- Exploratory data analysis
- Correlation analysis
- Feature scaling using StandardScaler

## Machine Learning
K-Means clustering was evaluated using:
- Elbow Method
- Silhouette Score

The final model uses **6 customer clusters**.

PCA was also used to visualize the clusters in two dimensions.

## Customer Segments
The identified segments include:

1. Low-Value / Inactive Customers
2. Regular High-Value Customers
3. Affluent Older Customers
4. Recent Low-Value Customers
5. Premium High-Value Customers
6. Older Low-Value Customers

## Key Outcome
The segmentation helps identify different customer groups based on their purchasing behavior and characteristics, which can support targeted marketing and customer engagement strategies.

## Project Files
- `Customer_Segmentation_KMeans.ipynb` — Complete analysis and machine learning workflow.
