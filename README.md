# Advanced Retinal Image Segmentation using U-Net Architecture  
## A Leap Forward in Ophthalmological Diagnostics
## Paper link In iEEE-https://ieeexplore.ieee.org/abstract/document/10914804

📄 *Published in:* 2024 Fourth International Conference on Advances in Electrical, Computing, Communication and Sustainable Technologies (ICAECT)  
📅 *Date:* January 11, 2024  
📍 *Pages:* 1–6  
📚 *Publisher:* IEEE  
🔗 *Citations:* Cited by 4 (as of 2024)

---

## 🧠 Overview

This repository supports the research paper:

> **"Advanced Retinal Image Segmentation using U-Net Architecture: A Leap Forward in Ophthalmological Diagnostics"**  
> *Authors:* Nobanul Hasan, Md Jahid Alam Riad, Stabak Das, Prosenjit Roy, Mahfuzur Rahman Shuvo, Mafizur Rahman

This work presents a novel approach for accurate retinal image segmentation leveraging the **U-Net convolutional neural network** architecture. Our objective is to assist ophthalmologists in diagnosing retinal diseases such as diabetic retinopathy and age-related macular degeneration (AMD) with higher precision and efficiency.

---

## 🔬 Research Focus

- Leveraging **U-Net**, a powerful encoder-decoder based deep learning model for biomedical image segmentation.
- Emphasis on segmenting intricate retinal structures such as:
  - Blood vessels
  - Optic discs
  - Lesions

- Dataset used for training and testing includes high-resolution retinal fundus images from publicly available ophthalmology datasets such as DRIVE, STARE, and CHASE_DB1.

---

## 📊 Key Highlights

- **U-Net-based segmentation model** tailored for pixel-level classification of retinal components.
- High **Dice coefficient** and **IoU (Intersection over Union)** scores achieved for multiple test scenarios.
- Model architecture fine-tuned for low-resource deployment while retaining diagnostic accuracy.

| Metric         | Score (Average) |
|----------------|-----------------|
| Dice Coefficient | ~0.88         |
| IoU (Jaccard Index) | ~0.81     |

---

## 🗂️ Repository Structure

```bash
├── data/                   # Preprocessing scripts and data loaders
├── model/                  # U-Net implementation and weights
├── notebooks/              # Jupyter notebooks for training and evaluation
├── results/                # Predicted masks and visual outputs
├── paper/                  # Published paper and citation
└── README.md               # Project summary and usage
