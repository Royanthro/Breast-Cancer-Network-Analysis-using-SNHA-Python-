# Breast-Cancer-Network-Analysis-using-SNHA-Python-
This project applies the St. Nicolas House Algorithm (SNHA) to the Wisconsin Breast Cancer dataset to construct and analyze correlation-based networks. It includes graph visualization with matplotlib and networkx, and identifies central nodes using key centrality measures (degree, betweenness, eigenvector).
# 🧪 Breast Cancer Network Analysis using SNHA (Python)

This project demonstrates how to apply the **St. Nicolas House Algorithm (SNHA)** for discovering meaningful relationships among features in the **Wisconsin Breast Cancer dataset**. By transforming the dataset into a correlation-based network, we visualize and analyze variable interdependencies to support feature insight, potential biomarker discovery, and exploratory data analysis in medical datasets.

---

## 📌 Features

* ✅ Loads and preprocesses the Wisconsin Breast Cancer dataset using `pandas`.
* ✅ Computes correlation matrices (`spearman`) between features.
* ✅ Applies SNHA to derive a directed/undirected feature interaction graph.
* ✅ Visualizes the correlation graph and SNHA-inferred network using `matplotlib`.
* ✅ Converts the SNHA network into a `NetworkX` graph for further analysis.
* ✅ Calculates key centrality metrics:

  * **Degree Centrality**
  * **Betweenness Centrality**
  * **Eigenvector Centrality**
* ✅ Identifies the most influential/central features in the dataset.
* ✅ Visualizes node importance through graph layout and size scaling.
* ✅ Ready for export to GraphML/GML for Gephi, Cytoscape, or further machine learning analysis.

---

## 🧰 Tools & Libraries Used

* `snha4py` – SNHA Python implementation
* `pandas` – Data handling
* `matplotlib` – Plotting
* `networkx` – Graph analysis
* `numpy` – Matrix operations

---

## 📈 Use Case

Understanding how different features (such as cell radius, texture, perimeter, etc.) interact within malignant or benign tumors can help uncover diagnostic patterns. SNHA helps by generating a statistically meaningful network of these interactions, and NetworkX centrality metrics highlight which features are structurally important.

---

## 📁 Folder Structure

```
.
├── data/
│   └── breast_cancer_wisconsin.csv
├── snha_analysis.py
├── network_analysis.py
├── visualization.py
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/snha-breast-cancer-analysis.git
   cd snha-breast-cancer-analysis
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the analysis:**

   ```bash
   python snha_analysis.py
   ```

---

## 📀 Output

* Graphical plots of:

  * True (original) correlation graph
  * SNHA-derived predicted graph
  * NetworkX graph with central nodes
* Printout of top nodes by centrality
* Optional export to GraphML or CSV


---

### 👤 Author

**Soumyajit Singha Roy**
Data Science | Network Analysis | SNHA Researcher
