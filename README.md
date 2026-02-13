# from scratch

ML fundamentals, implemented from scratch.

## SVD (Singular Value Decomposition)

Decomposes any matrix into **U · Σ · Vᵀ** — revealing its hidden structure as rotations and stretches.

Built using only `numpy` and two core ideas:
- **Power iteration** — find the most important direction by repeated multiplication
- **Deflation** — peel it off, find the next

📓 [`svd/svd.ipynb`](svd/svd.ipynb)
