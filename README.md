
## Summary 
Reproducibility of Deep Learning Feature Extractors for Mammographic Malignancy Classification and Synthetic Radiogenomic Marker Prediction
This repository contains the complete Python-based experimental pipeline for evaluating the reproducibility, robustness, and generalizability of deep learning feature extractors in mammographic malignancy classification. The study uses the CBIS-DDSM dataset with 10 independent patient-level train–test partitions to investigate performance variability across five pretrained architectures: ResNet18, ResNet50, MobileNetV2, DenseNet121, and ViT-B/16.
The framework evaluates three machine learning classifiers—Random Forest, Logistic Regression, and Support Vector Machine (SVM)—alongside feature representation similarity, prediction agreement, calibration, statistical significance, and hyperparameter sensitivity. It also incorporates a controlled experiment using four synthetic radiogenomic proxy markers (BRCA1, BRCA2, TP53, and HER2), which are generated from pathology-dependent probabilities rather than actual molecular measurements.
External validation using the MIAS dataset examines cross-dataset generalizability. The repository provides reproducible preprocessing, feature extraction, model evaluation, statistical analysis, computational profiling, and automated generation of publication-ready figures and result tables.

## 📊 Datasets

This project uses the following publicly available mammography datasets:

| Dataset | Purpose | Source |
|---|---|---|
| **CBIS-DDSM** | Cancer outcome prediction and mammographic image analysis | [Cancer Imaging Archive](https://www.cancerimagingarchive.net/collection/cbis-ddsm/) |
| **MIAS Mammography** | Mammographic image classification and analysis | [Kaggle](https://www.kaggle.com/datasets/kmader/mias-mammography) |

### Dataset Details

#### 🩻 CBIS-DDSM
- **Full Name:** Curated Breast Imaging Subset of DDSM
- **Source:** The Cancer Imaging Archive (TCIA)
- **Application:** Breast cancer detection and outcome prediction
- **Dataset:** [CBIS-DDSM](https://www.cancerimagingarchive.net/collection/cbis-ddsm/)

#### 🩺 MIAS Mammography
- **Full Name:** Mammographic Image Analysis Society (MIAS)
- **Source:** Kaggle
- **Application:** Mammographic image analysis and classification
- **Dataset:** [MIAS Mammography](https://www.kaggle.com/datasets/kmader/mias-mammography)
