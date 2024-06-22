# Median Filter and Canny Edge Detection Project

## Overview

This project demonstrates the application of Median Filtering and Canny Edge Detection using NVIDIA's NPP (NVIDIA Performance Primitives) library. These image processing techniques are implemented to leverage GPU acceleration for efficient processing of images.

## Features

1. **Median Filter**: Reduces noise in images by replacing each pixel with the median value from a surrounding window of pixels.
2. **Canny Edge Detection**: Identifies edges in images using a multi-stage algorithm involving noise reduction, gradient calculation, non-maximum suppression, and edge tracking by hysteresis.

## Requirements

- CUDA Toolkit
- NPP Library
- C++ Compiler
- Makefile

## How to Run
Change the directory till medianFilterCannyEdgeNPP Folder.
After that run
1. make clean build
2. make run
### 1. Clone the Repository

```sh
git clone https://github.com/jay20438/GPUCoure3.git
cd GPUCoure3
