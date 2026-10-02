# Efficient Facial Emotion Recognition Using Residual Squeeze-and-Excitation and Enhanced Inception Networks

This repository contains the official source code, architectural configurations, and replication scripts for the paper: **"Efficient Facial Emotion Recognition Using Residual Squeeze-and-Excitation and Enhanced Inception Networks"**, published in the *Proceedings of the 2026 9th International Conference on Computational Intelligence in Data Science (ICCIDS)*.

## IEEE Copyright Notice

> © 2026 IEEE. Personal use of this material is permitted. Permission from IEEE must be obtained for all other uses, in any current or future media, including reprinting/republishing this material for advertising or promotional purposes, creating new collective works, for resale or redistribution to servers or lists, or reuse of any copyrighted component of this work in other works.

***

## Abstract
This article introduces a new deep convolutional neural network model for facial emotion recognition by fusing residual squeeze-and-excitation blocks with enhanced inception modules. Tested on the FER2013 dataset, the model achieves 93.31% accuracy with only 4.1 million parameters while maintaining high precision and recall across all seven emotion classes for real-time systems.

***

## Table of Contents
- [Key Features](#key-features)
- [Repository Structure](#repository-structure)
- [Installation & Quickstart](#installation--quickstart)
- [Citation](#citation)
- [Keywords](#keywords)

***

## Key Features
* **Hybrid Core Architecture:** Integrates depthwise separable convolutions within an enhanced Inception framework to minimize total parameters to **4.1 Million**.
* **Channel Attention Optimization:** Implements Residual Squeeze-and-Excitation (SE) blocks for channel-wise feature re-weighting.
* **Real-Time Efficiency:** Validated consistency across all seven standard emotion classes.

## Repository Structure
```text
├── data/FER2013/             # Place FER2013 dataset here
├── src/
│   ├── models/               # Inception & SE block implementations
│   ├── utils/                # Data augmentation scripts
│   ├── train.py              # Training pipeline
│   └── evaluate.py           # Evaluation script
├── requirements.txt
└── README.md
```

## Installation & Quickstart
Clone the repository and install dependencies:
```bash
git clone https://github.com
cd Efficient-FER-ResidualSE-Inception
pip install -r requirements.txt
python src/train.py --batch_size 64 --epochs 120 --lr 0.001
```

***

## Citation
```bibtex
@INPROCEEDINGS{10407590,
  author={Desai, V. and Sheth, A. and Puthran, S.},
  booktitle={2026 9th International Conference on Computational Intelligence in Data Science (ICCIDS)}, 
  title={Efficient Facial Emotion Recognition Using Residual Squeeze-and-Excitation and Enhanced Inception Networks}, 
  year={2026},
  pages={1-6},
  doi={10.1109/ICCIDS69108.2026.11407590}}
```

## Keywords
`Emotion recognition` • `Computational modeling` • `Computer architecture` • `Data science` • `Data augmentation` • `Real-time systems` • `Data models` • `Computational efficiency` • `Convolutional neural networks` • `Testing` • `Facial emotion recognition` • `Squeeze-and-Excitation blocks` • `Inception modules`
