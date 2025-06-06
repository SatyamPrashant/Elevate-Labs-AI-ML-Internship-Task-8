# Task 8: Elevate Labs AI/ML Internship K-Means Clustering – Mall Customer Segmentation

---

## Dataset
- **Mall_Customers.csv**
- Columns used: `Annual Income`, `Spending Score`
- Goal: Segment customers into similar spending profiles

## Steps Performed
1. **Data Loading & Scaling**
   - Used `StandardScaler` to normalize features

2. **Optimal K Selection**
   - Applied **Elbow Method** (plot WCSS vs. K)
   - Chose **K=5** based on the inflection point

3. **KMeans Clustering**
   - Fitted with `KMeans(n_clusters=5)`
   - Assigned `Cluster` labels to each customer

4. **Cluster Visualization**
   - 2D scatter plot using income and score
   - Different clusters in different colors

5. **Evaluation**
   - **Silhouette Score** ≈ 0.55–0.60 indicating decent separation

---

## Interview Insights
- **KMeans** groups data by minimizing within-cluster variance (WCSS)
- **Elbow Method** helps pick the best `K`
- **Silhouette Score**: Measures cohesion vs. separation (closer to 1 is better)

---
