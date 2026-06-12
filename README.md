# Image Compression using SVD and NMF

## Overview
This project demonstrates image compression using matrix factorization techniques from Linear Algebra.

Two approaches were implemented:

- Singular Value Decomposition (SVD)
- Non-Negative Matrix Factorization (NMF)

The goal is to reduce image storage requirements while preserving visual quality through low-rank approximations.

## Features

- Image reconstruction using different ranks (k)
- Comparison of SVD and NMF compression
- Mean Squared Error (MSE) analysis
- Compression ratio evaluation
- Visualization of reconstructed images
- Singular value decay analysis

## Technologies Used

- Python
- NumPy
- Scikit-Learn
- Matplotlib
- SciPy

## Results

- SVD achieved better reconstruction quality at lower ranks.
- NMF provided interpretable parts-based representations.
- Increasing rank improved image quality while reducing compression efficiency.

## Concepts Used

- Linear Algebra
- Matrix Factorization
- Eigenvalues and Eigenvectors
- Singular Value Decomposition
- Non-Negative Matrix Factorization
