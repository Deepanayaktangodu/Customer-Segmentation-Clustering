Customer Segmentation Using Clustering (Python)
📌 Project Overview

This project applies K-Means Clustering to segment customers based on demographic and behavioral attributes from the Customer Personality Analysis dataset.
The aim is to identify distinct customer groups and provide data-driven marketing recommendations for targeted campaigns.

📂 Repository Structure
Customer-Segmentation-Clustering/
│── data/
│   └── marketing_campaign.csv              # Dataset
│── notebooks/
│   └── customer_segmentation.ipynb         # Jupyter Notebook with full workflow
│── reports/
│   └── customer_segmentation_report.pdf    # Final Report (PDF)
│── images/
│   └── elbow_plot.png
│   └── pca_clusters.png
│   └── cluster_comparison.png
│── README.md                               # Project overview
│── requirements.txt                        # Python dependencies

🛠 Tools & Technologies

Python: Data preprocessing, clustering, visualization

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Jupyter Notebook: Development environment


📊 Methodology

Data Preparation

Cleaned dataset, handled null values, converted date formats

Created new feature: Customer_Since_Days

Removed irrelevant columns (ID, Z_CostContact, Z_Revenue)


Feature Engineering

Encoded categorical variables (Education, Marital_Status)

Standardized features using StandardScaler


Clustering

Used Elbow Method to determine optimal K (=3)

Applied K-Means Clustering and assigned cluster labels


Visualization

Elbow Plot: To select optimal clusters

PCA Scatter Plot: Visualizing customer groups in 2D

Cluster Comparison Chart: Feature differences among clusters

Cluster Profiling & Insights

Cluster 0 – Luxury Loyalists: High income, premium spenders → VIP offers, exclusive previews

Cluster 1 – Budget Buyers: Low income, low spending → Discounts, bundles, re-engagement

Cluster 2 – Value Seekers: Moderate income, active buyers → Loyalty rewards, cross-selling


📈 Results & Business Impact

Identified 3 distinct customer personas

Enabled targeted marketing strategies for each cluster

Provides a roadmap for improving customer engagement and ROI


🚀 How to Run

Clone this repository
git clone https://github.com/your-username/Customer-Segmentation-Clustering.git
cd Customer-Segmentation-Clustering

Install dependencies
pip install -r requirements.txt

Open the Jupyter Notebook
jupyter notebook notebooks/customer_segmentation.ipynb

📌 Future Improvements

Perform RFM Analysis (Recency, Frequency, Monetary) for deeper insights

Experiment with Hierarchical Clustering and DBSCAN

Automate marketing strategy dashboards in Power BI/Tableau


📑 Deliverables

📝 Jupyter Notebook (full code)

📊 Visualizations (Elbow, PCA, Cluster Comparison)

📄 Final Report (PDF)

✨ This project demonstrates the power of unsupervised learning in deriving business insights and supports data-driven decision making for marketing strategies.
