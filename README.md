# GraphML: Movie Recommendation System with Graph Neural Networks

This project explores the use of **Graph Neural Networks (GNNs)** to build a movie recommendation system based on user-movie interaction data. It was developed as part of the CS346 course project.

## 📂 Repository Contents

- `final.ipynb` — Jupyter notebook containing the full implementation of the GNN-based recommendation system.
- `u.data` — User-movie rating dataset (based on MovieLens 100k format).
- `Project_Proposal.pdf` — Initial project proposal outlining objectives, methods, and expected outcomes.
- `Group_26.pdf` — Project presentation slides.
- `FinalReport.docx` — Final report documenting the methodology, experiments, and findings.

## 🚀 Objective

To build a personalized movie recommendation system that learns from user behavior and item relationships using GNN architectures — leveraging the graph structure of users and movies rather than relying solely on traditional collaborative filtering.

## 🛠️ Technology Stack

- **Python**
- **PyTorch / PyTorch Geometric** (for GNN modeling)
- **Jupyter Notebook**
- **pandas / numpy / scikit-learn** (for preprocessing and evaluation)

## 📊 Dataset

The dataset is derived from the [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/100k/), formatted as:


A bipartite graph is constructed where:
- Nodes represent users and movies.
- Edges represent interactions (ratings).

## 🔍 Approach

1. **Data Preprocessing**: Construct a bipartite graph from the rating matrix.
2. **Graph Construction**: Users and movies are modeled as nodes; interactions as edges.
3. **Modeling**: Train a GNN (e.g., GCN and GraphSAGE) to learn embeddings for users and movies.
4. **Prediction**: Use dot product or MLP-based scoring between user and movie embeddings.
5. **Evaluation**: Evaluate with metrics like RMSE 
