# umapPLUS

This repository contains an implementation of the smooth_knn_dist function, an improved method for computing the smooth k-nearest neighbors (k-NN) distance in the context of the UMAP algorithm. This method offers significant computational advantages compared to the original approach while maintaining the quality of the embedding results.

## Features

Efficient computation of smooth k-NN distances using binary search and NumPy vectorization.
Improved execution times compared to the original UMAP algorithm.
Scalability to handle high-dimensional datasets with a large number of features.

## Installation

To use the smooth_knn_dist function, you need to have the following dependencies installed:

1. Python 3.x
2. NumPy
3. Numba

You can install the required dependencies using pip:

pip install numpy

pip install numba

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## Acknowledgments

This implementation is based on the original UMAP algorithm by McInnes, L., Healy, J., & Melville, J. (2018). We would like to acknowledge their contribution to the field of dimensionality reduction and manifold learning.
