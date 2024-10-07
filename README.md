# Autoencoder-for-Dimension-Reduction-on-Fashion-MNIST

This project uses an autoencoder to perform dimensionality reduction on the Fashion MNIST dataset, specifically focusing on two classes: Pullover and Dress. The goal is to reduce the original 784-dimensional images (28x28) into a lower-dimensional representation of 128 dimensions, while preserving important features for accurate reconstruction.

#### Approach
Baseline Autoencoder: The initial model reduces the image dimensions and reconstructs them. The quality of the reconstruction is evaluated using the Structural Similarity Index (SSIM).
Model Improvement: The autoencoder’s architecture was modified, and hyperparameters were fine-tuned to improve the SSIM score, leading to better reconstruction results.

#### Dataset
The dataset is sourced from the Fashion MNIST dataset, which can be accessed here: https://github.com/zalandoresearch/fashion-mnist

