# Task_8

# Customer Segmentation using K-Means Clustering

This project applies K-Means clustering to segment customers based on their **Age**, **Annual Income (k$)**, and **Spending Score (1-100)**.

## Dataset

The dataset consists of:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Objective

To identify distinct customer groups using unsupervised machine learning (K-Means Clustering) and understand their behaviors for potential marketing strategies.

## Steps Followed

1. **Data Loading & Preprocessing**
   - Loaded the dataset using Pandas
   - Selected features: `Age`, `Annual Income`, `Spending Score`
   - Scaled the data for better clustering performance

2. **Finding Optimal Clusters**
   - Used the Elbow Method to determine the optimal number of clusters
   - **Optimal k found: 5**

3. **Model Training**
   - Applied KMeans with `k=5`
   - Added cluster labels to the dataset

4. **Visualization**
   - PCA was used to reduce dimensions for 2D plotting
   - Clustered customers were visualized using Seaborn

5. **Evaluation**
   - Calculated Silhouette Score to assess cluster quality

## Results

- The Elbow method indicated **5 clusters** as optimal
- Customers were segmented into 5 meaningful groups
- Visual analysis helped understand the spending behavior across age/income groups

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Credits
Dataset by VJ Choudhary on [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
