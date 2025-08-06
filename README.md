# 🧠 Detecting Adrenal Lesions in CT Scans using Deep Learning

This pilot project, developed for the **NHS AI Lab Skunkworks team**, explores the application of deep learning and computer vision to improve the detection of **adrenal lesions** in CT scans. It aims to validate the technical feasibility of automating this process to support radiologists with faster, more consistent assessments.

---

## 📌 Project Summary

Adrenal lesions are found in approximately **6% of individuals** post-mortem — often without prior diagnosis. In the UK alone, around **50,000 patients are affected annually**. While some lesions are benign, others may be malignant and require further investigation.

Currently, detection relies on **manual interpretation** of CT scans by radiologists — a time-consuming and subjective task. This project investigates a **deep learning–based approach** to automatically identify adrenal lesions from CT imaging data.

---

## 🔐 Data Protection

- This project was covered by a **Data Protection Impact Assessment (DPIA)**
- Fully compliant with the **UK Data Protection Act 2018** and **UK GDPR**
- **No personal data** or trained models are shared in this repository

---

## 🧠 Technical Overview

The project implements a **2.5D binary classification model** to detect adrenal lesions in 3D CT scans. Key steps include:

- 🏗️ **Preprocessing:** Extracting 2.5D slices from 3D volumes
- 🧠 **Model Architecture:** Deep learning CNN tailored for medical imaging
- 🧪 **Training:** Model trained and evaluated using appropriate validation strategies

> The codebase consists of modular Jupyter notebooks covering data loading, preprocessing, model training, and evaluation.

---

## 📂 Repository Structure

