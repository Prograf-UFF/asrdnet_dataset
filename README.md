# ASRDNet Dataset: Asian Soybean Rust Segmentation

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

---

## 🇺🇸 English Description

This repository contains the dataset used in the paper **"ASRDNet: A new image-segmentation neural network model for detecting Asian rust on soybean leaves"**. The dataset consists of 63 high-resolution RGB images of soybean leaves infected with Asian Soybean Rust (ASR), caused by the fungus *Phakopsora pachyrhizi*.

The images were provided by **Embrapa** and annotated by three independent expert phytopathologists. The goal of this dataset is to provide a benchmark for semantic segmentation of plant diseases, specifically dealing with lesion morphology variations.

### Directory Structure

The dataset is organized into three main folders:

1.  [cite_start]**`original_images/`**: Contains the raw RGB images of the leaves.
2.  [cite_start]**`probabilistic_mask/`**: Contains masks representing the vote count of the 3 experts (agreement level).
3.  [cite_start]**`binary_mask/`**: Contains the final consensus (2 votes or more) binary masks used for model training (lesion vs. background).

### File Naming
All folders contain 63 images, named consistently from `image1.png` to `image63.png` to ensure easy matching between input and ground truth.
