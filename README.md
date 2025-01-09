# Content Based Image Retrieval

This repository provides an implementation of an image-based search system using feature extraction with a pre-trained ResNet50 model and nearest neighbor search. The system allows users to find images similar to a given query image from a dataset.

# Features
- Image Preprocessing: Resizes and preprocesses images for feature extraction.
- Feature Extraction: Uses ResNet50 pre-trained on ImageNet to extract feature embeddings.
- Image Search: Employs the k-Nearest Neighbors (kNN) algorithm for finding similar images.
- Visualization: Displays the query image and its top-k similar images.
