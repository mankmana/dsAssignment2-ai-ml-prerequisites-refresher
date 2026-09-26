# Linear Algebra for Deep Learning

This notebook explains the core linear algebra concepts used in deep learning and connects them directly to neural-network operations using NumPy and visualizations.

## Links

- **Executed Google Colab:** [Open Colab](https://colab.research.google.com/drive/1vIvyM5dFHbFvt_sVeD7la_vABGPqyp4i?usp=sharing)
- **YouTube Walkthrough:** [Watch Video](https://youtu.be/LGH_BUtPxt4)

## Topics Covered

- Scalars, vectors, matrices, and tensors
- Tensor shapes in deep learning
- Vector addition
- Scalar multiplication
- Dot product
- Cosine similarity
- Hadamard product
- Bias addition and residual connections
- Matrix addition
- Matrix-vector multiplication
- Matrix-matrix multiplication
- Batch processing in neural networks
- Dense-layer computation using `X @ W + b`
- Matrix transpose
- Transpose in attention mechanisms
- Query-Key multiplication using `Q @ K.T`
- Matrix inverse
- Identity matrix
- Determinants
- Singular matrices
- Eigenvalues and eigenvectors
- Principal Component Analysis (PCA)
- L1, L2, and infinity norms
- Regularization
- Frobenius norm
- ReLU activation
- Softmax
- Two-layer neural-network forward pass using NumPy

## Key Takeaways

- Neural-network computations are largely based on vectors, matrices, tensors, and matrix multiplication.
- A single neuron performs a dot product between inputs and weights and then adds a bias.
- A complete dense layer can process an entire batch using `X @ W + b`.
- Dot products are also useful for measuring similarity between vectors and embeddings.
- Transpose operations make computations such as `Q @ K.T` possible in attention mechanisms.
- Determinants help describe whether a matrix transformation preserves or collapses dimensions.
- Eigenvalues and eigenvectors identify important directions in a transformation and are used in PCA.
- Norms measure vector and matrix size and are commonly used in regularization.
- A neural-network forward pass combines matrix multiplication, bias addition, activation functions, and probability calculations such as softmax.
