# NLOS Object Detection & Localization

This repository implements machine learning models for **Non-Line-of-Sight (NLOS)** object detection — focusing on both **classification** (identifying the object) and **localization** (pinpointing its position) using indirect signal data.

---

## 📌 Project Goals

- Develop models capable of detecting and localizing objects hidden from direct view using NLOS data.
- Compare multiple modeling strategies for classification and localization.
- Provide reusable code, experiment notebooks, and a pre-trained checkpoint for quick inference.

---

## 📂 Repository Structure

nlos-object-detection-localization/  
├── data/ # Includes input data and preprocessing scripts  
├── model.ipynb # Core Jupyter notebook with modeling implementation  
├── simple_data_test.ipynb # Notebook for preliminary data exploration & testing  
├── reg_cls_checkpoint.pt # Pretrained checkpoint (classification/localization)  
└── README.md # Project documentation  
