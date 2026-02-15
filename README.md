# from scratch

ML fundamentals, implemented from scratch.

## SVD (Singular Value Decomposition)

Decomposes any matrix into **U · Σ · Vᵀ** — revealing its hidden structure as rotations and stretches.

Built using only `numpy` and two core ideas:
- **Power iteration** — find the most important direction by repeated multiplication
- **Deflation** — peel it off, find the next

📓 [`svd/svd.ipynb`](svd/svd.ipynb)

## PCA (Principal Component Analysis)

Finds the directions that matter most in your data — dimensionality reduction via SVD on centered data.

Built on top of the SVD implementation above:
- **Center** the data, compute eigenvectors of AᵀA
- **Project** onto the top-k principal components

📓 [`pca/pca.ipynb`](pca/pca.ipynb)
