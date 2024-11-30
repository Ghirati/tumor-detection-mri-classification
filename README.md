# Iran Annual AI Competition - MRI Binary Classification

This repository contains the code and resources for the **Iran Annual AI Competition** (IAAA), focused on the binary classification of MRI images.

- **Competition Host**: [IAAA Platform](https://iaaa.ai/)  
- **Dataset**: [IAAA MRI Challenge on Kaggle](https://www.kaggle.com/datasets/iaaaplatform/iaaa-mri-challenge)

---

## Overview

This project aims to develop machine learning models for analyzing MRI images, specifically T1, T2, and T2-FLAIR sequences.

---

## TODO List

- [ ] **Skull stripping**: Explored available solutions but did not find suitable repositories for implementation.  
- [ ] **Metadata usage**: Plan to integrate DICOM metadata into the fully connected layer of the model.  
- [ ] **Bias field correction**: Considered but abandoned due to excessive execution time.  
- [ ] **Histogram equalization**: Evaluated but found to degrade image quality, so it was not adopted.

---

## References

- **Model Repository**: This project utilizes models from the [timm_3d repository](https://github.com/ZFTurbo/timm_3d).  
- **Pretrained Weights**: [Download weights](https://kaggle.com/datasets/9422031e2101b7d38c8633d0e7eb6cd937f4756dd01b83e248e07d227ebcfcad).
