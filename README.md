# Autoencoder-for-Dimension-Reduction-on-Fashion-MNIST

This project uses an autoencoder to perform dimensionality reduction on the Fashion MNIST dataset, specifically focusing on two classes: Pullover and Dress. The goal is to reduce the original 784-dimensional images (28x28) into a lower-dimensional representation of 128 dimensions, while preserving important features for accurate reconstruction.

## Dataset
The dataset is sourced from the Fashion MNIST dataset, which can be accessed here: https://github.com/zalandoresearch/fashion-mnist. It includes various images of clothing items, specifically the Pullover and Dress classes.

## Approach
To start, I built a baseline autoencoder model that reduces the dimensions of the images and reconstructs them. I measured the quality of the reconstructed images using the Structural Similarity Index (SSIM), which helps determine how similar the output is to the original image.

Next, I improved the model by modifying its architecture and fine-tuning the hyperparameters. These adjustments helped increase the SSIM score, leading to better reconstruction quality.

## Results
The modified autoencoder achieved improved SSIM scores, demonstrating that it effectively reduced the image dimensions while preserving important features. This project shows how useful autoencoders can be for tasks that involve simplifying image data without losing critical information.
