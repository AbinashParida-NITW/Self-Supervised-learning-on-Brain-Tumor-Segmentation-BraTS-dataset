Brain Tumor Segmentation using Self-Supervised Learning
Overview
This repository contains the code and report for the project on brain tumor segmentation using a self-supervised learning framework.
The project leverages a convolutional autoencoder to extract meaningful features from unlabelled MRI scans and utilizes these features for the downstream task of brain tumor segmentation.

Table of Contents
Introduction
Dataset
References

Introduction
Medical image analysis is essential for diagnosing diseases and guiding medical interventions. This project aims to develop a self-supervised learning framework for medical image analysis, leveraging unlabelled data to learn meaningful representations for downstream tasks such as tumor segmentation.

Dataset
The dataset used in this project is the BraTS (Brain Tumor Segmentation) dataset, which includes MRI scans with four modalities (FLAIR, T1, T1CE, and T2) and corresponding segmentation masks.
The dataset can be accessed here.
References
BraTS dataset: https://www.kaggle.com/code/rastislav/3d-mri-brain-tumor-segmentation-u-net/input
Relevant literature on self-supervised learning and autoencoders
