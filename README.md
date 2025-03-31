# Retinal Fundus Image Analysis

![Retinal Fundus seg using maskr](https://github.com/Addisu-Amare/demo_maskr/blob/main/0328.gif) 
![Retinal Fundus seg using yolo11s-seg and yolo11n-seg](https://github.com/Addisu-Amare/demo_maskr/blob/main/yolo-seg.gif)
*(Retinal fundus image  segmentation)*

## Overview
This repository contains tools and models for analyzing retinal fundus images, with applications in:
- **Disease Detection** (e.g., diabetic retinopathy, glaucoma, AMD)
- **Anatomical Structure Segmentation** (optic disc, blood vessels, lesions)
- **Clinical Biomarker Extraction** (cup-to-disc ratio, vessel tortuosity)
- **Quality Assessment** of fundus images

---

## Key Features
- **Preprocessing**: Standardization of fundus images (cropping, contrast enhancement).
- **Deep Learning Models**: Pretrained models for classification/segmentation tasks.
- **Quantitative Analysis**: Metrics for clinical relevance (e.g., hemorrhage area calculation).
- **Visualization Tools**: Overlay masks, heatmaps, or annotations on fundus images.

---

## Dataset
### Supported Datasets
- [Kaggle Diabetic Retinopathy](https://www.kaggle.com/c/diabetic-retinopathy-detection)
- [EyePACS](https://www.kaggle.com/c/diabetic-retinopathy-detection/data)
- [STARE](https://cecas.clemson.edu/~ahoover/stare/) or [DRIVE](https://drive.grand-challenge.org/) (vessel segmentation)
- Custom datasets (see `data/README.md` for formatting guidelines)

### Dataset Structure
