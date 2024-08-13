# Medical Imaging and Knowledge Representation

This repository contains practical works completed during the IMA204 course "Imagerie médicale et biologique / Représentation des connaissances" (Medical and Biological Imaging / Knowledge Representation) at Télécom Paris.

## Table of Contents
1. [Course Overview](#course-overview)
2. [Learning Objectives](#learning-objectives)
3. [Practical Works](#practical-works)
   - [Image Registration](#1-image-registration)
   - [Statistical Shape Analysis](#2-statistical-shape-analysis)
   - [Parametric Active Contours & Level Set](#3-parametric-active-contours--level-set)
   - [Medical Image Segmentation](#4-medical-image-segmentation)
4. [Research Paper Presentation](#research-paper-presentation)
5. [Technologies Used](#technologies-used)
6. [Author](#author)
7. [Acknowledgments](#acknowledgments)

## Course Overview

This course covers several key areas in medical imaging and knowledge representation:

1. Physics principles of Medical and Biological Imaging
2. Image registration and Statistical Shape Analysis
3. Deformable Models
4. Introduction to graphs and their use in matching and segmentation
5. Overview of structural medical imaging, including acquisition techniques and image processing applications

## Learning Objectives

- Model and solve image registration and interpretation problems using approaches ranging from low-level to structural formalisms.
- Discover the field of medical imaging and its applications (registration, filtering, segmentation).
- Understand the physics principles behind medical and biological imaging techniques.
- Gain practical experience with deformable models and statistical shape analysis.

## Practical Works

### 1. Image Registration

Focus: Implementing and testing image registration techniques.

Key components:
- Geometric transformations
- Forward and inverse image warping
- Application to simple shapes and hand images
- Comparison with existing libraries
- Optional: Lucas-Kanade algorithm implementation

### 2. Statistical Shape Analysis

Focus: Implementing landmark-based image registration and statistical shape analysis techniques.

Key components:
- Affine and Procrustes registration for aligning landmark configurations
- Generalized Procrustes Analysis (GPA) algorithm
- Principal Component Analysis (PCA) for shape variability analysis
- Visualization of shape deformation modes

Dataset: Facial landmarks

### 3. Parametric Active Contours & Level Set

Focus: Image segmentation using deformable models.

Key components:
- Image preprocessing and edge detection
- Classic snakes and gradient vector flow (GVF) snakes implementation
- Chan-Vese segmentation using level sets
- Geometric active contours with balloon forces

### 4. Medical Image Segmentation

Focus: Medical image segmentation using K-means clustering as a pre-segmentation tool.

Key components:
- Working with CT scans, brain MRI, and cardiac MRI sequences
- Preprocessing techniques (morphological operations, filtering)
- K-means clustering implementation
- Post-processing for segmentation refinement
- Full segmentation pipeline development
- Comparison with ground truth and quality metrics computation

## Research Paper Presentation

Paper: Orkisz, Maciej, et al. "Segmentation of the pulmonary vascular trees in 3D CT images using variational region-growing." *Irbm* 35.1 (2014): 11-19.

Key points:
- Objective: Segmentation of pulmonary vascular trees in 3D CT scans
- Method: Variational region growing within a lung mask
- Evaluation: Using VESSEL12 challenge framework
- Results: Overall specificity of 0.938 and sensitivity of 0.772

## Technologies Used

- Python
- NumPy
- Matplotlib
- SciPy
- scikit-image (skimage)
- OpenCV (cv2)
- IPython/Jupyter Notebooks

## Author

Adnane El Bouhali

## Acknowledgments

- Télécom Paris
- Course instructors: Elsa ANGELINI and Pietro GORI
- Teaching assistants
