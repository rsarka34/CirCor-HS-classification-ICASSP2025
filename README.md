# CirCor-HS-classification-ICASSP2025

**A Unified Joint Contrastive Triplet Loss with Temporal and Frequency Signal Fusion for Diagnosing Heart Murmurs (ICASSP-2025)**

**Authors: Ayushi Pal, Arka Roy, Udit Satija**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rsarka34/CirCor-HS-classification-ICASSP2025/blob/main/model/ModelICASSP2025.ipynb)
[![Paper Link](https://img.shields.io/badge/Paper%20Link-IEEE%20Xplore-green)](https://ieeexplore.ieee.org/abstract/document/10889389)
[![Paper Link](https://img.shields.io/badge/Supplementary-material-red)](https://github.com/rsarka34/CirCor-HS-classification-ICASSP2025/blob/main/PPT/ICASSP_slides%20(2).pdf)
<img width="1501" alt="Screenshot 2025-03-21 at 11 07 14 AM" src="https://github.com/user-attachments/assets/25c31f42-cb01-4051-a92a-cee44998509f" />

# Abstract
<p align="justify">
Heart murmurs are a prevalent indication of cardiovascular diseases and can offer valuable insights into early cardiac abnormalities. For the prompt diagnosis and treatment of any cardiac problems, their early identification and examination are essential for reducing the death risks. In this paper, we introduce the joint contrastive triplet loss for fusing the cross-domain and intra-domain embeddings obtained from the time and frequency signals to diagnosis of heart murmurs. For this, we examine the phonocardiogram (PCG) signals given in the circor digiscope heart sound database for three-class classification i.e., murmur present (HMP), murmur absent (HMA), and murmur unknown (HMU). The outcomes of the experiment demonstrate that the proposed work outperforms the existing works and attains an accuracy of 89.87% for three classes, along with additional performance measures such as 90.08% precision, 89.87% recall, and 89.89% F1-score.
</p>

# Methodology
<img width="1143" alt="Screenshot 2025-03-12 at 10 24 33 AM" src="https://github.com/user-attachments/assets/474b2a67-15b0-4668-aec0-23e445820750" />

<p align="center">
<img width="599" alt="Screenshot 2025-03-12 at 10 30 30 AM" src="https://github.com/user-attachments/assets/e79eef02-7b77-4f7b-8322-2063a591608f" />
</p>

# Dataset
**Circor Digiscope Dataset:**  [![Dataset Link](https://img.shields.io/badge/CirCor%20Data-Physionet%20Data-red)](https://physionet.org/content/circor-heart-sound/1.0.3/)   [![Paper Link](https://img.shields.io/badge/Paper%20Link-IEEE%20Xplore-green)](https://ieeexplore.ieee.org/document/9658215)

![pp](https://github.com/user-attachments/assets/0c53b249-61a6-461c-8425-92e79ca77d55)

# Results
<p align="center">
  <img width="1143" alt="Screenshot 2025-04-11 085657" src="https://github.com/user-attachments/assets/7680e163-9dcb-40ea-96f4-8abbd4116cb5" />
</p>

<p align="center">
<img width="810" alt="Screenshot 2025-03-12 at 10 37 21 AM" src="https://github.com/user-attachments/assets/2dd3c23a-bdf0-48c0-8370-d8b4fe620381" />
</p>

# Performance
<p align="center">
<img width="1365" alt="Screenshot 2025-03-12 at 10 36 04 AM" src="https://github.com/user-attachments/assets/1024c0c8-1ed5-43ba-884f-d39e940bb16f" />
</p>


# Cite as
A. Pal, A. Roy and U. Satija, "A Unified Joint Contrastive Triplet Loss with Temporal and Frequency Signal Fusion for Diagnosing Heart Murmurs," *ICASSP 2025 - 2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)*, Hyderabad, India, 2025, pp. 1-5, doi: 10.1109/ICASSP49660.2025.10889389.

```bibtex
@INPROCEEDINGS{10889389,
  author={Pal, Ayushi and Roy, Arka and Satija, Udit},
  booktitle={ICASSP 2025 - 2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)}, 
  title={A Unified Joint Contrastive Triplet Loss with Temporal and Frequency Signal Fusion for Diagnosing Heart Murmurs}, 
  year={2025},
  volume={},
  number={},
  pages={1-5},
  keywords={Heart;Support vector machines;Time-frequency analysis;Accuracy;Databases;Contrastive learning;Signal processing;Nearest neighbor methods;Speech processing;Phonocardiography;Cardiovascular disorder (CVD);heart murmurs (HM);phonocardiogram (PCG);supervised contrastive learning based triplet network},
  doi={10.1109/ICASSP49660.2025.10889389}}
