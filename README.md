# E--commerce-Customer-Segmentation-using-Cluster-Classification-Algorithm

Objectives
Clustering:

Segment customers using unsupervised learning algorithms like K-Means and Hierarchical Clustering.
Determine the optimal number of clusters using methods such as the Elbow Method and Silhouette Score.
Visualize clusters using Principal Component Analysis (PCA).
Classification:

Train supervised models (e.g., Random Forest, Logistic Regression) to predict customer segments.
Validate the performance using cross-validation techniques and test sets.
Evaluate models using metrics like accuracy, precision, recall, and F1-score.
Feature Engineering:

Extract and create meaningful features from transactional data, including TotalAmount and PCA-reduced dimensions.
Pipeline Development:

Build a streamlined pipeline from data preprocessing to clustering and classification.
Dataset
The dataset contains transactional data from a UK-based retailer, including the following fields:

InvoiceNo: Unique transaction identifier
StockCode: Product code
Description: Product description
Quantity: Number of items purchased
InvoiceDate: Date of transaction
UnitPrice: Price per unit
CustomerID: Unique customer identifier
Country: Customer location
Key Features:
Engineered features such as TotalAmount (Quantity × UnitPrice) and PCA components for dimensionality reduction.
Cleaned data by handling missing values, duplicates, and outliers.
Project Workflow
Data Cleaning and Preprocessing:

Removed invalid or incomplete data (e.g., missing CustomerID, negative quantities).
Scaled numerical features and encoded categorical variables.
Clustering:

Performed K-Means and Hierarchical Clustering to group customers.
Determined the optimal number of clusters using the Elbow Method and Silhouette Scores.
Analyzed clusters to understand customer behavior and spending patterns.
Classification:

Trained models like Random Forest to predict customer segments.
Split data into training, validation, and test sets to ensure robust evaluation.
Validated models using cross-validation and tested on unseen data.
Evaluation and Visualization:

Assessed model performance using metrics such as accuracy, precision, recall, and F1-score.
Visualized clusters and classification results using PCA.
Tools and Libraries
Python: Core language for implementation.
Libraries:
pandas, numpy for data manipulation and preprocessing.
matplotlib, seaborn for data visualization.
scikit-learn for clustering, classification, and evaluation.
Key Results
Identified meaningful customer segments using K-Means and Hierarchical Clustering.
Achieved high classification accuracy in predicting customer segments using Random Forest.
Provided actionable insights into customer behaviors for targeted marketing strategies.
