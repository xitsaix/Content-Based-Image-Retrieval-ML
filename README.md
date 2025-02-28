# Content Based Image Retrieval

This repository provides an implementation of an image-based search system using feature extraction with a pre-trained ResNet50 model and nearest neighbor search. The system allows users to find images similar to a given query image from a dataset.

## Features
- Image Preprocessing: Resizes and preprocesses images for feature extraction.
- Feature Extraction: Uses ResNet50 pre-trained on ImageNet to extract feature embeddings.
- Image Search: Employs the k-Nearest Neighbors (kNN) algorithm for finding similar images.
- Visualization: Displays the query image and its top-k similar images.

## Requirements
To run the code, install the following dependencies:

```bash
pip install numpy tensorflow scikit-learn matplotlib opencv-python
```

## Usage
1. Preprocessing and Feature Extraction
The Preprocessing and Feature Extraction step involves extracting features from all images in the dataset.

2. Indexing and Search Implementation
The Indexing and Search Implementation step involves loading preprocessed features and paths to perform a similarity search.

3. Display Search Results
Visualize the query image along with the top-k similar images


## Dataset
Place dataset in the ./datasets directory. The system supports images in .jpg, .jpeg, or .png formats.

## How to Run
To run the system, follow these steps:
1. Run the feature extraction script
2. Use the indexing and search script to query similar images.
3. Visualize the results with the provided show_images function.
