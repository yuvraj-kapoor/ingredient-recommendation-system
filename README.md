# 🍳 Ingredient Recommendation System

A **C-based ingredient recommendation system** that models food relationships using graph theory, adjacency matrices, and recursive graph traversal algorithms.

---

## 🚀 Overview

This project analyzes ingredient relationships by representing ingredients as nodes in a graph. Connections between ingredients are determined by how frequently they appear together in recipes.

The system uses:
- adjacency matrices
- recursive graph traversal
- ingredient similarity analysis
- graph-based recommendation logic

to explore ingredient relationships and suggest compatible substitutions.

The project demonstrates practical applications of:
- graph theory
- recursion
- matrix-based data structures
- recommendation systems

---

## ✨ Features

- Load ingredient relationship graphs from datasets
- Analyze ingredient connectivity
- Find related ingredients
- Compute k-distance ingredient relationships
- Generate ingredient substitution recommendations
- Perform restricted graph traversal
- Analyze ingredient co-occurrence networks
- Support both small and large graph datasets

---

## 🧠 Key Concepts

- Graph theory
- Adjacency matrices
- Recursive traversal
- Network analysis
- Recommendation systems
- Matrix data structures
- Algorithmic problem solving
- Data-driven relationship modeling

---

## 🌐 Graph Representation

Each ingredient is represented as a node in a graph.

Connections between ingredients are weighted based on:
- frequency of co-occurrence in recipes

The graph is stored using:
- adjacency matrices

Example:

```text
Ingredient A ---- 15 ---- Ingredient B
```

Meaning:
- the two ingredients appeared together in 15 recipes.

---

## ⚙️ Core Functionalities

### 🔍 Ingredient Lookup
Search for ingredients and retrieve graph indices.

### 🧩 Related Ingredients
Identify ingredients commonly paired together.

### 🌐 K-Distance Relationships
Explore ingredient relationships multiple connections away.

### 🔄 Ingredient Substitution
Suggest replacement ingredients based on graph similarity.

### 🚫 Restricted Traversal
Analyze ingredient relationships while excluding selected nodes.

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/yuvraj-kapoor/ingredient-recommendation-system.git
```

2. Navigate into the project folder:

```bash
cd ingredient-recommendation-system
```

3. Compile the project:

```bash
gcc -Wall A3_driver.c
```

4. Run the executable:

```bash
./a.out
```

---

## 🧪 Sample Functionality

Example queries:
- related ingredients for garlic
- substitute recommendations for basil
- ingredient relationship traversal
- recipe network exploration

Example ingredient dataset includes:
- garlic
- basil
- onion
- chicken
- oregano
- cumin
- rosemary

---

## 📂 Project Structure

```text
├── ingredient_graph_system.c   # Main graph analysis implementation
├── A3_driver.c                 # Driver/testing program
├── AdjMat_small.dat            # Small adjacency matrix dataset
├── AdjMat_full.dat             # Full adjacency matrix dataset
├── Ingredient_names_small.txt  # Small ingredient list
├── Ingredient_names_full.txt   # Full ingredient list
├── README.md
```

---

## ⏱ Time Complexity

| Operation | Complexity |
|---|---|
| Ingredient Lookup | O(n) |
| Graph Traversal | O(n²) |
| K-Distance Search | O(n²) |
| Ingredient Recommendation | O(n²) |
| Matrix Processing | O(n²) |

---

## 📌 Notes

- Developed as part of a university computer science assignment.
- Focused on graph theory and recursive algorithms.
- Demonstrates practical applications of recommendation systems and network analysis.
- Emphasizes matrix-based graph representations and recursive traversal logic.

---

## 🔮 Future Improvements

- Recipe recommendation engine
- Graph visualization tools
- Weighted recommendation scoring
- GUI implementation
- Machine learning integration
- Real-time recipe analysis

---

## 👨‍💻 Author

**Yuvraj Kapoor**  
Computer Science Student
