# Priciple Component Analysis (PCA)

I have implemented Principal Component Analysis (PCA) from scratch, using the underlying mathematical concepts, in order to gain a deeper understanding of the processes and transformations that occur behind the scenes in the PCA functions provided by built-in libraries.

Standardize the data (optional, depending on scale).
1. Compute mean of each feature in dataset.
2. Centralize the dataset.
3. Compute the covariance matrix.
4. Compute the eigenvalues and eigenvectors of the covariance matrix.
5. Sort the eigenvalues and eigenvectors in descending order.
6. Select the top 𝑘 eigenvectors to form the principal components.
7. Project the original data onto the new k-dimensional subspace.
8. (Optional) Analyze the explained variance to decide how many principal components to keep.
