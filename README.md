#  Customer Segmentation using K-Means Clustering

## Overview

This project uses **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers based on their purchasing behavior. It helps businesses understand different types of customers and target them effectively.

---

## Dataset

* **Name:** Mall Customers Dataset
* **Features:**

  * Customer ID
  * Gender
  * Age
  * Annual Income
  * Spending Score

---

## Objective

* Segment customers based on **Annual Income** and **Spending Score**
* Identify different customer groups
* Help in improving marketing strategies

---

## Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

##  Workflow

1. Import libraries
2. Load dataset
3. Perform data analysis
4. Select relevant features
5. Use **Elbow Method** to find optimal clusters
6. Train K-Means model (`k = 5`)
7. Visualize clusters

---

##  Results

* Customers are grouped into **5 clusters**
* Each cluster represents a different spending behavior:

  * High income – High spending
  * High income – Low spending
  * Low income – High spending
  * Low income – Low spending

---

## How to Run

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

```bash
jupyter notebook
```

Open:

```
Customer_Segmentation_using_K_Means_Clustering.ipynb
```
## Conclusion

K-Means clustering helps in identifying customer segments effectively. This enables businesses to:
* Improve marketing strategies
* Target customers better
* Increase profitability

---

## Future Improvements
* Use more features for better segmentation
* Try other clustering algorithms (DBSCAN, Hierarchical)
* Deploy as a web app

---

## 🙌 Author

Bethireddy Bhargavi
