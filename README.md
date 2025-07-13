# 📊 Graph Subgraph Classification Tool

A Python-based tool to **classify and prioritize subgraphs** in an undirected graph file. It identifies and ranks **cliques**, **chains**, **stars**, and **cycles** using a mix of **graph traversal algorithms** and **structural heuristics**.

---

## 🚀 Features

- ✅ **Supports Weighted and Unweighted Graphs**
- 🔍 **Classifies Graphs Into:**
  - **Cliques** (fully connected subgraphs)
  - **Chains** (linear paths of connected nodes)
  - **Stars** (central node with ≥ 3 independent neighbors)
  - **Cycles** (loops of 3+ nodes)
- 📐 **Subgraph Prioritization Based on:**
  - Size (number of nodes)
  - Total edge weight
  - Structural density

---

## 🛠️ Technologies Used

- **Python 3.x**
- **NetworkX** – For graph representation and analysis
- **itertools** – For combinatorial logic
- **collections** – For structured result storage

---

## 📂 Input Format

Graph input should be a `.txt` file where each line represents an edge:

A B 1.5
B C 2.0
C D
D A


- Edge weights are optional. If not provided, the weight defaults to 1.0.

---

## 📦 Installation & Setup

```bash
git clone https://github.com/your-username/graph-subgraph-classification.git
cd graph-subgraph-classification
pip install networkx
