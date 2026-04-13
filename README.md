# Domain-Robust Pneumonia Detection using MobileNetV2

**Multi-Dataset Research Pipeline for Edge Device Deployment**

A comprehensive PyTorch-based research project exploring **cross-domain generalization** in pneumonia detection from chest X-ray images. The pipeline evaluates domain shift challenges across three diverse datasets and tests practical, lightweight domain adaptation techniques suitable for **edge devices**.

---

## 📋 Table of Contents
- Overview
- Key Features
- Datasets
- Research Contributions
- Model Architecture
- Experiments
- Results Highlights
- Installation & Setup
- Usage
- Project Structure
- Deployment Feasibility
- Citation
- License

---

## Overview

Chest X-ray based pneumonia detection models often suffer from significant **domain shift** when deployed in real-world clinical settings due to differences in imaging equipment, patient demographics, and acquisition protocols.

This repository implements a systematic research pipeline using **MobileNetV2** to:
- Quantify the impact of domain shift across datasets
- Evaluate unsupervised domain adaptation methods
- Demonstrate feasibility for edge deployment

---

## Key Features

- Lightweight model (~2.2M parameters)
- Multi-dataset support
- Domain adaptation (BN adaptation, TTA)
- Full evaluation metrics
- Edge deployment analysis

---

## Datasets

- Kermany
- CheXpert
- RSNA Pneumonia

---

## Research Contributions

- Cross-dataset evaluation
- Lightweight architecture
- Unsupervised adaptation
- Reproducible setup

---

## Model Architecture

- MobileNetV2 backbone
- Frozen feature extractor
- Custom classifier head

---

## Experiments

- Independent training
- Cross-dataset testing
- Mixed training
- Domain adaptation
- Architecture comparison

---

## Results Highlights

- Cross-domain drop observed
- Adaptation improves performance
- Small model size (~8–10MB)

---

## Installation

```bash
git clone https://github.com/yourusername/domain-robust-pneumonia-detection.git
cd domain-robust-pneumonia-detection
pip install torch torchvision numpy pandas matplotlib
```

---

## Usage

Run:
```
pneumonia_detection.ipynb
```

---

## Project Structure

```
├── pneumonia_detection.ipynb
├── README.md
├── requirements.txt
```

---

## Deployment

- Edge-friendly
- Low memory
- Fast inference

---

