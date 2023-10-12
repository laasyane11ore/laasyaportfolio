---
title: "Image Classification using CIFAR-10 Dataset "
description: "Engineering Applications of Machine Learning "
dateString: April 2023
draft: false
tags: ["Python", "Machine Learning", "TensorFlow", "scikit-learn", "CNN", "KNN", "PCA", "KDE"]
weight: 201
cover:
    image: "home/cifarimg.png"
---

## Introduction
This project showcases my skills in deep learning and data analysis using TensorFlow, scikit-learn, and other Python libraries. In this project, I perform image classification and analysis on the CIFAR-10 dataset, which contains 60,000 32x32 color images in 10 different classes, such as airplanes, automobiles, birds, cats, and more.
<!-- projects/obsidian-publish-github-action/cover -->
<!-- 
![my notes](/projects/obsidian-publish-github-action/img1.jpg) -->

<!-- So, if you want to view my notes exactly like I do, you can clone my [**Obsidian Vault**](https://github.com/arkalim/obsidian-vault) repository and download **Obsidian** to render it. But, this solution isn't elegant as it would require you to download an additional software. So, I along with my college roommate, [**Sarthak Narayan**](https://sarthaknarayan.tech/), had been working over the past 2 weeks on the project, [**Obsidian Publish using GitHub Action**](https://github.com/project-cool/obsidian-publish-action), which would allow us to effortlessly publish our notes as a static website.  -->

<!-- It is complete and I've used it to publish my notes at [**notes.arkalim.org**](https://notes.arkalim.org).
![published notes](/projects/obsidian-publish-github-action/img2.jpg) -->

## Technologies
- TensorFlow: For building and training deep learning models.
- Scikit-learn: For data preprocessing, dimensionality reduction, and traditional machine learning.
- Matplotlib and Seaborn: For data visualization and generating informative plots.
- Gaussian Naive Bayes, Kernel Density Estimation, and K-Nearest Neighbors: For traditional machine learning classification.
- Principal Component Analysis (PCA): For dimensionality reduction.
- StandardScaler: For feature scaling.

## Project Highlights
### Data Loading and Preprocessing 
- Imported TensorFlow and loaded the CIFAR-10 dataset.
- Explored the dataset's structure and dimensions.
- Normalized pixel values to the range [0, 1].
- Flattened the images and converted labels to 1D arrays.
- Visualized sample images from the dataset.
### Dimensionality Reduction and Traditional Machine Learning
- Applied PCA to reduce the dimensionality of the dataset.
- Trained Kernel Density Estimation (KDE) models for each class.
- Utilized Gaussian Naive Bayes for classification.
- Evaluated models using accuracy and generated classification reports.
- Created confusion matrices and heatmaps for visualizing model performance.
### Deep Learning Model
- Built a convolutional neural network (CNN) using TensorFlow's Keras API.
- Compiled the model with the Adam optimizer and sparse categorical cross-entropy loss.
- Trained the CNN on the CIFAR-10 dataset with data augmentation.
- Plotted training and validation accuracy over epochs.
- Evaluated the model's performance on the test set.
- Visualized a confusion matrix as a heatmap.
### Real-Time Image Classification
- Demonstrated real-time image classification using the trained CNN.
- Loaded a test image, made predictions, and displayed results.
## Conclusion
This project combines traditional machine learning techniques with deep learning to classify images from the CIFAR-10 dataset. It showcases data preprocessing, dimensionality reduction, model building, and evaluation, making it a valuable addition to my portfolio to demonstrate my skills in computer vision and machine learning.

<!-- ## Final thoughts
Having an automated way to publish your notes online with the community is a powerful way to share knowledge. This project has also made it exceedingly easy for me to refer my notes from anywhere, which is powerful when you work on a lot of systems. -->

<!-- ## Resources
- [My Notes](https://notes.arkalim.org)
- [Obsidian Publish - GitHub Action](https://github.com/project-cool/obsidian-publish-action)
- [Parser and Image Compressor](https://github.com/project-cool/obsidian-to-mkdocs)
- [MkDocs - Material Theme](https://squidfunk.github.io/mkdocs-material/) -->