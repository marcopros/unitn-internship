# 3D Reconstruction from Synthetic Datasets

This project was developed as part of an internship at the **University of Trento** and focuses on **3D reconstruction** from synthetic datasets using two main techniques: **COLMAP** and **SuGaR**.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset Preparation](#dataset-preparation)
3. [Methods Used](#methods-used)
   - [COLMAP](#colmap)
   - [SuGaR](#sugar)
4. [Results and Analysis](#results-and-analysis)
5. [Dataset Information](#dataset-information)
6. [Visualization of Results](#visualization-of-results)

---

## Project Overview

The goal of the project is to perform 3D reconstruction from synthetic datasets using two methods:
- **COLMAP**: A tool that uses Structure-from-Motion (SfM) and Multi-View Stereo (MVS) to generate 3D models.
- **SuGaR**: A newer method based on **3D Gaussian Splatting**.

The project evaluates these two methods in terms of performance, accuracy, and the quality of the resulting models.

---

## Dataset Preparation

Nine synthetic datasets were generated using the [nerf-dataset-creator-plugin](https://github.com/AndreaMas/nerf-dataset-creator-plugin). The datasets include both **outdoor** (5) and **indoor** (4) scenes.

---

## Methods Used

### COLMAP

- **COLMAP** is a photogrammetry software used to perform 3D reconstruction. It combines **Structure-from-Motion (SfM)** with **Multi-View Stereo (MVS)** to create accurate point clouds and mesh models.

### SuGaR

- **SuGaR** is a newer approach for 3D reconstruction that utilizes **3D Gaussian Splatting**. While visually compelling, SuGaR is evaluated in this project for its performance compared to the traditional COLMAP method.

---

## Results and Analysis

The project compares COLMAP and SuGaR in terms of:
- **Accuracy** of the resulting 3D models
- **Execution speed**
- **Handling of flat and low-detail surfaces**

The comparison is performed using **CloudCompare** for visual and quantitative evaluation of the generated models.

---

## Dataset Information

| Info                | Value              |
|---------------------|--------------------|
| **Number of datasets** | 9                |
| **Dataset Type**     | Indoor/Outdoor     |
| **File Size**        | ~1GB per model     |
| **Images per dataset**| 250               |
| **Format**           | PNG                |
| **Resolution**       | 800x800            |

---

## Visualization of Results

You can view the 3D reconstruction results on Google Drive at the following link:

[View Results](https://drive.google.com/drive/folders/1TwfDqCzI4fV9StuTM7iw1mN32opuhV8B?usp=share_link)
