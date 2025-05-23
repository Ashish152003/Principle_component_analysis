Principal Component Analysis (PCA) is a dimensionality reduction technique used in data analysis and machine learning.

🧠 Concept (in simple terms):
Imagine you have data with many features (columns) — PCA helps you:

Identify the most important directions (called principal components) where the data varies the most.

Project the data into a smaller number of dimensions without losing much information.

💡 Why use PCA?
To reduce noise and speed up algorithms.

To visualize high-dimensional data (e.g., reduce 100D to 2D/3D).

To eliminate multicollinearity (highly correlated features).

📊 How PCA works (high level):
Standardize the data.

Compute the covariance matrix.

Calculate eigenvalues and eigenvectors of the covariance matrix.

Sort eigenvectors by eigenvalues (importance).

Select top k components to reduce dimensions.

Project data onto these principal components.

