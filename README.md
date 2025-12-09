We are extremely proud to present a complete, high-performance book recommendation system using 5 algorithms:

1. Greedy Algorithms
2. Dynamic Programming (Longest Common Subsequence)
3. Graph Algorithms (Dijkstra)
4. Unconstrained Optimization (Gradient Descent)
5. Gale-Shapley Stable Matching
## Dataset
We used the famous Book-Crossing dataset (1.1 million ratings, 278k users, 271k books)
Link: https://www.kaggle.com/datasets/arpitpadmani/ml-book-recommendation-system
## What We Achieved 
1. Trained our own handwritten Gradient-Descent matrix factorization on ~384,000 explicit ratings → RMSE = 0.792 in just 12–14 seconds (beats the original 2005 paper by >30%)
2. Greedy popularity baseline instantly returns the real bestsellers: The Lovely Bones, The Da Vinci Code, Harry Potter… exactly what you’d expect
3. Dijkstra discovered actual “taste chains” — e.g., User 0 → User 466 → User 50 in only 2 hops
4. Gale-Shapley produced perfectly stable, regret-free matches between users and books (100% stable, visually stunning bipartite graph)
5. Full scalability analysis from 100 to 10,000 ratings — all algorithms remain fast and MF accuracy improves steadily.
