# WAAM Porosity Segmentation using Deep Learning

This repository contains the implementation of deep learning models for automated porosity segmentation in Wire Arc Additive Manufactured (WAAM) aluminium alloys using X-ray Computed Tomography (XCT) images.

## Related Publication

Aditi Babu et al. (2026) 
"Deep Learning Assisted Insights on Porosity Evolution of WAAM Aluminium Alloys"
Journal of Process Mechanical Engineering.

## Overview
This work focuses on automating the segmentation of pores from XCT image slices using convolutional neural networks and analyzing porosity variation across different build regions in WAAM-fabricated aluminium alloys.

The study aims to reduce dependence on manual segmentation and improve the consistency of porosity characterization.

## Models Implemented
- U-Net
- U-Net + VGG
- DeepLab

## Dataset
The models were trained and evaluated on 2D XCT image slices obtained from WAAM-fabricated aluminium alloy samples.

Ground truth masks were generated through manual annotation and used for supervised learning.

## Maintainer
Aditi Babu

Original repository hosted on Prof. Shivraman Thapliyal’s account for publication purposes.
