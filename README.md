# SAR and Optical Image Fusion using U-Net

## Description

This repository contains code for my final year undergraduate project at ECE Department, SSN College of Engineering, Chennai, India, which involves the fusion of SAR and Optical Images of Satellite Remote Sensing Images using a deep learning model without a ground truth or a reference image. The code cotains an adaptation of the U2Fusion (Unsupervised Fusion) algorithm for the Sen 1-2 dataset for SAR-Optical Image Fusion. 

## Dataset
The dataset is image tiles of SAR and corresponding Optical Images from Sentinel-1 and Sentinel-2 Dataset made available publically. 
You can download the Sen 1-2 Dataset: https://mediatum.ub.tum.de/1436631

## U-Net Model

U2Fusion is an unsupervised fusion algorithm originally founded for problems like multi-focus and multi-exposure image fusion. https://ieeexplore.ieee.org/document/9151265

In this project, the U2Fusion algorithm has been modified and adapted to fuse a Synthetic Aperture Radar (SAR) and Optical (Multi-Spectral) Images to produce a single, high-resolution colorized SAR image. 

## Contributors
 - Nitish Kumar Murali
 - Nithin G R
