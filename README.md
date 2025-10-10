# Brain Tumor MRI Classification

A project developed for the [Iran Annual AI Competition (IAAA)](https://iaaa.ai/) to classify multi-sequence MRI scans for the presence of tumors.

For a fully rendered experience, open the notebook in [**nbviewer**](https://nbviewer.org/github/Ghirati/tumor-detection-mri-classification/blob/main/main.ipynb) or [**Google Colab**](https://colab.research.google.com/github/Ghirati/tumor-detection-mri-classification/blob/main/main.ipynb).

---

## Project Highlights
- **Task**: Binary classification to determine the presence of a tumor (Tumor vs. No Tumor).
- **Dataset**: [IAAA MRI Challenge](https://www.kaggle.com/datasets/iaaaplatform/iaaa-mri-challenge) from Kaggle, containing T1, T2, and T2-FLAIR sequences.
- **Model Architecture**: Utilized 3D CNN based on the [timm_3d repository](https://github.com/ZFTurbo/timm_3d).
