# MambaU-Lite: A Lightweight Model based on Mamba and Integrated Channel–Spatial Attention for Skin Lesion Segmentation

## Introduction
This repository provides the **official implementation** of the skin lesion segmentation model on the **ISIC-2018** and **PH2** datasets, as presented in the paper:  
> [**MambaU-Lite: A Lightweight Model based on Mamba and Integrated Channel-Spatial Attention for Skin Lesion Segmentation**](https://arxiv.org/pdf/2412.01405)

The proposed **MambaU-Lite** integrates **Mamba** and **CNN** modules in a hybrid architecture to achieve accurate segmentation results with **low computational cost**.

---

## Key Contributions
- **Lightweight hybrid model**: Combines the strengths of Mamba (sequence modeling) and CNN (local feature extraction) to improve segmentation performance while remaining computationally efficient.  
- **P-Mamba sub-module**: A novel sub-structure designed to efficiently learn features at different representation levels.  
- **Integrated channel–spatial attention**: Enhances the model’s ability to capture discriminative features in both channel and spatial dimensions.  
- **Benchmark results**: Achieves competitive performance on **ISIC-2018** and **PH2** datasets with fewer parameters than conventional segmentation networks.

---

## Dataset
This study uses two **well-known public skin lesion segmentation datasets**:
- [**ISIC-2018**](https://drive.google.com/drive/folders/1m8gvU9n9m_evWQ90NveRCOSaJ7BfoqvP?usp=drive_link)  
- [**PH2**](https://drive.google.com/drive/folders/1V2OjohTGLAVxXsvOSJyepc3JqGFc4s8u?usp=drive_link)
  
These datasets are standard benchmarks in medical image segmentation tasks related to skin lesion analysis.



