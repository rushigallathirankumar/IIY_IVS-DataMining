# IIY_IVS-DataMining
# 📊 Data Mining Lab Programs (Python - Jupyter Notebooks)

This repository contains implementations of fundamental **Data Mining algorithms and techniques** using Python. Each notebook demonstrates both the **concept** and its **practical implementation** on sample datasets.

These programs cover the complete data mining pipeline including **ETL, preprocessing, classification, clustering, similarity analysis, and association rule mining**.

---

## 📁 Contents & Program Explanation

### 🔹 Unit 1: ETL Process
- **File:** `Unit-1ETL.ipynb`

**Description:**
This program demonstrates the **ETL (Extract, Transform, Load)** process:
- Extracts raw data from files
- Cleans and transforms data (handling missing values, formatting)
- Loads processed data for further analysis

📌 *Use Case:* Preparing raw data before applying machine learning algorithms.

---

### 🔹 Unit 2: Data Preprocessing & Similarity

#### 🌦️ Preprocessing Weather Dataset
- **File:** `Unit-2PreprocessingWeather.ipynb`

**Description:**
- Handles missing and inconsistent data
- Converts categorical values into numerical format
- Applies normalization and data cleaning techniques

📌 *Use Case:* Improves data quality and ensures better model accuracy.

---

#### 📏 Similarity & Dissimilarity
- **File:** `Unit-2 Sim&Diss.ipynb`

**Description:**
This program calculates similarity between data objects using:
- Euclidean Distance
- Manhattan Distance
- Cosine Similarity

📌 *Use Case:* Used in clustering, recommendation systems, and pattern recognition.

---

### 🔹 Unit 3: Classification Algorithms

#### 🌳 ID3 & J48 Decision Tree
- **File:** `Unit-3ID3&J48.ipynb`

**Description:**
- Implements ID3 algorithm using entropy and information gain
- Demonstrates J48 (improved version of ID3)
- Builds a decision tree for classification tasks

📌 *Use Case:* Prediction systems such as loan approval, medical diagnosis, etc.

---

### 🔹 Unit 4: Association Rule Mining

#### 🛒 Apriori Algorithm
- **File:** `Unit-4AprioriAlgorithm.ipynb`

**Description:**
- Identifies frequent itemsets in datasets
- Generates association rules using support and confidence

📌 *Use Case:* Market basket analysis (e.g., products frequently bought together).

---

#### ⚡ FP-Growth Algorithm
- **File:** `Unit-4FPGrowthAlgorithm.ipynb`

**Description:**
- Efficient alternative to Apriori
- Uses FP-Tree structure to reduce computation
- Works well with large datasets

📌 *Use Case:* Large-scale pattern mining in business analytics.

---

### 🔹 Unit 5: Clustering Techniques

#### 🎯 K-Means Clustering
- **File:** `Unit-5K-MeanClustering.ipynb`

**Description:**
- Divides data into K clusters
- Assigns points to nearest centroid
- Updates centroids iteratively

📌 *Use Case:* Customer segmentation and grouping similar data.

---

#### 🌐 Hierarchical Clustering
- **File:** `Unit-5_Heiraracal.ipynb`

**Description:**
- Builds clusters using agglomerative (bottom-up) approach
- Visualizes clusters using dendrogram

📌 *Use Case:* Understanding hierarchical relationships in data.

---

## ⚙️ Requirements

- Python 3.x  
- Jupyter Notebook  

Install dependencies:


pip install numpy pandas matplotlib scikit-learn


---

## 🎯 Learning Outcomes

- Understand complete data mining workflow  
- Learn preprocessing and data cleaning techniques  
- Implement classification and clustering algorithms  
- Analyze patterns using association rules  
- Apply similarity measures in real-world scenarios
