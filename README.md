# Unsupervised-Learning-and-Clustering-Analysis
## Project Overview
This project applies unsupervised machine learning techniques to the Mall Customers dataset to identify customer segments based on age, annual income, and spending score.

The goal is to understand customer behavior and discover groups that businesses can use for targeted marketing strategies.

## Dataset
The dataset contains 200 customers and includes the following features:

- **Age:** Customer's age
- **Annual Income (k$):** Customer's annual income in thousands of dollars
- **Spending Score (1–100):** Score assigned based on customer spending behavior
- **Gender:** Customer gender

## Technologies Used
- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## Methodology
1. Loaded and explored the dataset.
2. Checked the data structure and summary statistics.
3. Selected relevant numerical features for clustering.
4. Standardized the features using feature scaling.
5. Used the Elbow Method and Silhouette Score to evaluate cluster counts.
6. Applied K-Means clustering with 5 clusters.
7. Visualized and analyzed the resulting customer segments.
8. Compared the results with hierarchical clustering.

## Key Results
The K-Means model with 5 clusters produced the following customer segments:

- **Cluster 0:** Lower-income customers with low spending scores.
- **Cluster 1:** Younger customers with moderate incomes and relatively high spending scores.
- **Cluster 2:** Higher-income customers with high spending scores.
- **Cluster 3:** Higher-income customers with low spending scores.
- **Cluster 4:** Older customers with moderate incomes and spending scores.

The five-cluster solution provides interpretable customer groups. Other cluster counts were also evaluated, so five clusters should be viewed as a practical choice rather than the only possible solution.

## Visualizations
The notebook includes:
- Elbow Method and Silhouette Score plots
- Customer cluster scatter plots
- Cluster size chart
- Customer feature distributions
- Standardized cluster profile heatmap
- PCA visualization

## How to Run
1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `Week3_Customer_Segmentation.ipynb` and run the cells in order.

## Conclusion
Clustering revealed distinct customer groups with different income and spending patterns. These insights can support customer profiling and targeted marketing decisions. However, clustering results are exploratory and should be validated with additional business data before making real-world decisions.

## Author
Add your name here.

## Project Repository
Add your GitHub repository URL here.
