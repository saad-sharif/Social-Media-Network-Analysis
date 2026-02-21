# Social Network Analysis – Instagram, Facebook & Twitter

## Project Overview

This project analyzes the **structural characteristics of social networks** across three major online platforms:
- **Instagram**
- **Facebook**
- **Twitter**

The objective is to understand how users are connected on each platform, identify influential nodes, and detect **communities** within each network. Multiple community detection algorithms are applied and compared to highlight structural differences across platforms.

---

## Objectives

- Compute descriptive network statistics such as:
  - Connectedness
  - Degree and centrality measures
- Detect communities within each social network
- Compare community detection results across different algorithms
- Visualize network structures and detected communities
- Draw conclusions on structural similarities and differences between platforms

---

## Data Sources

The analysis uses pre-processed network adjacency data stored in Excel files:

- `Facebook_Data.xlsx`
- `Twitter_Data.xlsx`
- `Instagram_Data.xlsx`

Each file represents a network graph where nodes correspond to users and edges represent connections or interactions.

---

## Technologies & Libraries Used

### Core Libraries
- Python
- numpy
- pandas
- warnings

### Network Analysis
- networkx
- networkx.algorithms.community

### Community Detection & Embeddings
- Girvan–Newman algorithm
- Kernighan–Lin algorithm
- node2vec
- gensim

### Evaluation
- scikit-learn
  - adjusted_rand_score

### Visualization
- matplotlib

---

## Installation

Clone the repository and install the required dependencies:

```bash id="47q5ec"
git clone https://github.com/your-username/social-network-analysis.git
cd social-network-analysis
pip install numpy pandas matplotlib networkx node2vec gensim scikit-learn
