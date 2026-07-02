# Credit-Card-Fraud-Detection-using-Clustering


##  Project Overview

This project focuses on detecting potentially fraudulent credit card transactions using **Unsupervised Machine Learning** techniques. Since fraudulent transactions are rare and often lack labeled data, clustering algorithms are used to identify unusual transaction patterns and anomalies.

The project demonstrates how clustering can help financial institutions detect suspicious activities and improve fraud prevention systems.

---

##  Objectives

* Analyze credit card transaction data.
* Identify hidden patterns in transaction behavior.
* Detect anomalies that may indicate fraudulent activities.
* Apply clustering techniques to group similar transactions.
* Visualize transaction clusters for better interpretation.

---

##  Dataset Information

The dataset contains credit card transaction records with multiple features representing transaction characteristics and customer behavior.

### Dataset Features

* Transaction Amount
* Transaction Time
* Customer Behavioral Features
* Statistical Transaction Attributes
* Additional anonymized variables used for fraud analysis

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

##  Machine Learning Techniques

### K-Means Clustering

K-Means groups transactions into clusters based on similarity. Transactions that fall far from normal clusters may be considered suspicious.

### Anomaly Detection

Transactions that significantly differ from normal customer behavior are flagged for further investigation.

---

##  Project Workflow

1. Load and explore the dataset.
2. Perform data cleaning and preprocessing.
3. Handle missing values and outliers.
4. Scale numerical features using feature normalization techniques.
5. Apply clustering algorithms to group transactions.
6. Analyze cluster distributions and identify anomalies.
7. Visualize results and interpret suspicious patterns.

---

##  Results

* Successfully grouped similar transactions into clusters.
* Identified abnormal transaction patterns that could indicate fraud.
* Demonstrated the effectiveness of unsupervised learning for fraud detection problems.

---

##  How to Run the Project

```bash
# Clone the repository
git clone https://github.com/your-username/credit-card-fraud-clustering.git

# Navigate to project directory
cd credit-card-fraud-clustering

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```

---

##  Project Structure

```text
├── Credit Card Fraud Detection using Clustering.ipynb
├── README.md
└── requirements.txt
```

---

##  Future Enhancements

* Compare multiple clustering algorithms such as:

  * DBSCAN
  * Hierarchical Clustering
  * Gaussian Mixture Models
* Develop a real-time fraud monitoring dashboard.
* Deploy the model using Streamlit.
* Integrate advanced anomaly detection techniques.

---

##  Business Impact

Fraud detection systems help financial institutions:

* Reduce financial losses.
* Improve customer trust and security.
* Detect suspicious activities in real time.
* Enhance risk management strategies.

---

##  Author

**Mohammed Murshid K**

Aspiring Data Scientist | Machine Learning Enthusiast | Data Analytics Practitioner


