# KMeans Clustering on Customer Churn Dataset

This project implements KMeans Clustering to segment customers based on their behavior using a Customer Churn dataset. The goal is to understand customer groups for better business strategies.

## Dataset

The dataset used for this project is the **Customer Churn** dataset, which includes various features related to customer demographics, account information, and service usage.

**Sample Features:**
- Gender
- SeniorCitizen
- Partner
- Dependents
- Tenure
- PhoneService
- MultipleLines
- InternetService
- OnlineSecurity
- TechSupport
- StreamingTV
- MonthlyCharges
- TotalCharges
- Churn

##  Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`

##  Data Preprocessing

- Loaded the dataset using pandas.
- Handled missing values in `TotalCharges`.
- Converted categorical variables into numerical using Label Encoding and OneHotEncoding.
- Selected numerical features relevant for clustering.
- Scaled the features using `StandardScaler` for normalization.

##  KMeans Clustering Process

1. **Elbow Method:**
   - Used to determine the optimal number of clusters by plotting the Within-Cluster-Sum-of-Squares (WCSS).
   - Selected optimal `k` based on the "elbow" point in the curve.

2. **Model Training:**
   - Trained a `KMeans` model using the selected number of clusters.
   - Fitted the model to the scaled dataset.

3. **Cluster Labels:**
   - Added predicted cluster labels to the dataset.
   - Analyzed the characteristics of each cluster.

##  Visualizations

- Plotted the Elbow Method curve.
- Used scatter plots to visualize cluster distribution on key feature combinations.
- Cluster centers were highlighted to show centroids.

##  Future Work

- Apply other clustering techniques like DBSCAN or Hierarchical Clustering.
- Visualize using PCA or t-SNE for dimensionality reduction.
- Use cluster insights for churn prediction or targeted marketing.

##  Author

- **Name**: Suraj Chaudhary
- **GitHub**: link
- **Email**: skc818527@gmail.com

##  Learnings

- Hands-on experience with unsupervised learning using `KMeans`.
- Preprocessing techniques like Label Encoding, OneHotEncoding, and Feature Scaling.
- Visualization techniques to interpret clusters.
- Importance of feature selection and normalization in clustering.


