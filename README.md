# Customer Segmentation using K-Means Clustering

### Overview

This project performs **customer segmentation** using the **K-Means Clustering** algorithm on the *Mall Customers* dataset. The goal is to understand customer purchasing behavior and identify distinct customer groups based on their **Age**, **Annual Income**, and **Spending Score**.

Although the dataset includes a “Spending Score,” it only describes *individual* customer behavior. K-Means helps uncover *hidden patterns* in the data — showing **which groups of customers exist** naturally (e.g., high-income high-spenders vs. low-income low-spenders).

These insights can help businesses:

* Personalize marketing strategies
* Improve customer retention
* Optimize sales campaigns

This data-driven segmentation helps businesses make more informed and targeted decisions.

### Tech Stack
**Libraries Used:**

  * `pandas`, `numpy` — data manipulation and analysis
  * `matplotlib`, `seaborn` — data visualization
  * `scikit-learn` — preprocessing, K-Means clustering, and evaluation


### Results & Insights

* Optimal number of clusters: **K = 5**
* Silhouette Score ≈ **0.45**, indicating well-separated clusters.
* While the dataset already contains attributes like *Spending Score* and *Income*, it doesn’t define how customers are related.
* K-Means Clustering automatically groups customers based on similarity across features — uncovering **natural customer segments** such as:

  1. **Premium Customers** – high income, high spending
  2. **Upsell Targets** – high income, low spending
  3. **Potential Growth Customers** – moderate income, high spending
  4. **Budget Customers** – low income, low spending
  5. **General Shoppers** – average income, average spending

These insights help tailor different marketing strategies — for example, loyalty rewards for premium customers and targeted promotions for budget-conscious ones.
