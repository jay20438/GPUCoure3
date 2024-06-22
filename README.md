# Median Filter and Canny Edge Detection Project

## Overview

This project demonstrates the application of Median Filtering and Canny Edge Detection using NVIDIA's NPP (NVIDIA Performance Primitives) library. These image processing techniques are implemented to leverage GPU acceleration for efficient processing of images.

## Dataset
For the assignment I have used the CMU FACE IMAGES Dataset(https://www.cs.cmu.edu/afs/cs.cmu.edu/project/theo-8/faceimages/faces/). The images in this dataset are in PGM format, which is similar to the format given in the NPP Box Filtering Laboratory.
## Techniques Used

1. **Median Filter**: Reduces noise in images by replacing each pixel with the median value from a surrounding window of pixels. I have used this algorithm as it is one of the altenative methods to box filtering.
2. **Canny Edge Detection**: It identifies edges in images using a multi-stage algorithm involving noise reduction, gradient calculation, non-maximum suppression, and edge tracking by hysteresis. I have used this algorithm for finding edge detection in the input images.

## Files
medianFilterCannyEdgeNPP/
│
├── cmu_face_images/
│   ├── subfolder1/
│   │   ├── image1.jpg
│   │   ├── image2.jpg
│   │   └── ...
│   ├── subfolder2/
│   │   ├── image3.jpg
│   │   └── ...
│   └── ...
│
├── medianFilterCannyEdgeNPP/
│   ├── Makefile
│   ├── medianFilterCannyEdgeNPP
│   ├── medianFilterCannyEdgeNPP.cpp
│   └── medianFilterCannyEdgeNPP.o
│
├── cmu_face_medianFilter/
│   ├── subfolder1/
│   │   ├── image1_medianFilter.jpg
│   │   ├── image2_medianFilter.jpg
│   │   └── ...
│   ├── subfolder2/
│   │   ├── image3_medianFilter.jpg
│   │   └── ...
│   └── ...
│
└── cmu_face_cannyedge/
    ├── subfolder1/
    │   ├── image1_cannyEdge.jpg
    │   ├── image2_cannyEdge.jpg
    │   └── ...
    ├── subfolder2/
    │   ├── image3_cannyEdge.jpg
    │   └── ...
    └── ...


## Requirements

- CUDA Toolkit
- NPP Library
- C++ Compiler
- Makefile

## How to Run
Change the directory till medianFilterCannyEdgeNPP Folder.
cd GPUCoure3-main
After that run
1. make clean build
2. make run

## How to View the Results
You can view the output images by either install an application like Bitberry File Opener or simply viewing on some PGM file viewer website.
### 1. Clone the Repository

```sh
git clone https://github.com/jay20438/GPUCoure3.git
