# Movie-Recommendation

# 🎬 Movie Recommendation System

This repository contains the implementation of a movie recommendation engine.

The system leverages three core techniques to provide personalized movie suggestions:
- ✅ User-Based Collaborative Filtering
- ✅ Item-Based Collaborative Filtering
- ✅ Pixie-Inspired Graph-Based Random Walks

---

## Repository Contents

| File / Folder                      | Description                                                              |
|-----------------------------------|--------------------------------------------------------------------------|
| `Movie_Recommendation.ipynb`      | Main Jupyter notebook containing full implementation and outputs         |
| `ratings.csv`                     | Cleaned user-movie ratings data from Part 1                              |
| `movies.csv`                      | Cleaned movie metadata from Part 1                                       |
| `users.csv`                       | Cleaned user demographic data from Part 1                                |
| `Pixie_Algorithm_Explanation.md`  | Document explaining the Pixie-inspired graph-based recommendation method |
| `Recommendation_Report.md`        | Detailed report covering methodology, results, and evaluation            |

> All CSVs (`ratings.csv`, `movies.csv`, `users.csv`) were created in **Part 1** and exported as required.

---

##  Techniques Implemented

### 1. User-Based Collaborative Filtering
- Computes cosine similarity between users based on their movie ratings
- Recommends movies liked by users with similar preferences

### 2. Item-Based Collaborative Filtering
- Calculates similarity between movies based on shared user ratings
- Recommends movies similar to a selected movie

### 3. Pixie-Inspired Graph-Based Recommender
- Constructs a bipartite graph of users and movies
- Performs random walks to uncover indirect relationships
- Recommends frequently visited movies based on walk frequency

---


##  How to Run

**Clone the repository**:
```bash
git clone https://github.com/your-username/Movie-Recommendation.git
cd Movie-Recommendation
```
**Install Requirements**:
```bash
pip install -r requirements.txt
```
**Run the Notebook**:
```bash
jupyter notebook Movie_Recommendation.ipynb
```
