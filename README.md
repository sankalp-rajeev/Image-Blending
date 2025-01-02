# Image Blending with Gaussian and Laplacian Pyramids

## Author
**Sankalp Rajeev**

## Overview

This project was part of my assignment for the Computer Vision course at Carnegie Mellon University

This repository encompasses the robust techniques of image processing, particularly the art of blending two images using Gaussian and Laplacian pyramids. These methodologies leverage the unique features of Gaussian and Laplacian pyramids to ensure seamless transitions between images and maintain image integrity.

## Key Concepts

- **Gaussian and Laplacian Pyramids**: Understand the foundational theory behind these pyramids and their relevance in image processing.

- **Pyramid Construction**: Dive deep into the techniques to construct Gaussian and Laplacian pyramids. This includes gaussian filtering and deriving the residuals or details lost during downsampling.

- **Image Reconstruction**: Explore the science of reconstructing the original image from its pyramidal components.

- **Image Blending**: Blend two distinct images to achieve a seamless transition, using the Gaussian and Laplacian pyramids.

## Repository Structure

### Image Pyramids

- `gaussianPyramid()`: Generates a Gaussian pyramid from a given image by iteratively applying a Gaussian filter and downsampling the image.

- `laplacianPyramid()`: Builds a Laplacian pyramid by calculating the residual details lost during the Gaussian filtering process.

- `pyramidToImage()`: Revives an image from its foundational base and the corresponding residuals from the Laplacian pyramid.

### Image Blending

The project provides a profound look into the process of image blending using the constructed Gaussian and Laplacian pyramids. The ultimate aim is to blend two distinct images in such a manner that there's a flawless transition from one image to the other.

## Inspiration

This work has been motivated and informed by the image blending techniques elucidated in the "Introduction to Visual Computing" course by Dr. Fernando Flores-Mangas.

## Final Thoughts

This project has been an enlightening journey into the nuances of image processing. By blending images using pyramids, we can see the profound impact of leveraging spatial frequencies in images. For anyone keen on diving deep into image processing, this repository serves as both a practical and theoretical resource.
