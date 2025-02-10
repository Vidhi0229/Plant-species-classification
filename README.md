# Plant-species-classification

## Project Overview
This project aims to develop an automated plant species identification system using deep learning techniques. By analyzing leaf images from the Swedish Leaf and Flavia datasets, the system will accurately classify different plant species. This will simplify plant recognition and enhance public awareness of plant life, contributing to education, conservation, and research efforts.

## Methodology
The system follows these key steps:

- Data Collection & Preprocessing: Gather leaf images from the Swedish Leaf and Flavia datasets.
- Resize and normalize images to ensure consistency.
- Synthetic Data Generation: Use a style-based GAN to generate synthetic leaf images for each plant species.
- Feature Extraction: Extract features from both real and synthetic images using ResNet-101 and EfficientNet-B0.
- Classification: Use extracted features for plant species classification with SVM and Random Forest classifiers.


## datasets
In this project, I utilize two datasets from the following sources:
- [Flavia](https://flavia.sourceforge.net/)
- [Swedish](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/)

## Results
    • FLAVIA:
        ◦ SVM
            ▪ Training set: 96.25%
            ▪ Test set: 93.15%
        ◦ RANDOM FOREST:
            ▪ Training set: 97.50%
            ▪ Test set: 93.25%
    • SWEDISH
        ◦ SVM
            ▪ Training set: 93.66%
            ▪ Test set: 90.89%
        ◦ RANDOM FOREST:
            ▪ Training set: 96.73%
            ▪ Test set: 90.69%

> Note: This project is still a work in progress and currently under research, with ongoing efforts aimed at improving accuracy.

## Authors
**Vidhi Srivastava**
- [GitHub](https://github.com/Vidhi0229)
- [LinkedIn](https://www.linkedin.com/in/vidhisrivastava01/)

## Show Your Support ⭐️⭐️
If you find this proposed methodology interesting, please consider giving it a star!
