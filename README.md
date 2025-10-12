# Low-Light Image Quality Enhancement using Bayesian Optimization

This repository contains the source code for our paper:

**"Low-Light Image Quality Enhancement through Bayesian Optimization using Gaussian Processes"**,  
accepted for presentation at **CROS 2025**.

---

## Overview

![Low-Light Image Enhancement](https://drive.google.com/uc?id=1Ipvor3RHr-TubrkmrgV1tjNHWCRvZTgI) 

Enhancing image quality under low-light conditions is a crucial challenge for autonomous robotic systems, especially in tasks such as navigation, inspection, and search-and-rescue operations, where visual data reliability directly impacts decision-making and performance. Low-light environments often degrade image quality, compromising the ability of robots to detect, classify, and interact with objects effectively.

This project proposes a novel approach that improves low-light image quality by combining:

- Brightness adjustment  
- Contrast enhancement  
- Noise reduction  

The optimal parameters for these operations are determined using **Bayesian Optimization with Gaussian Processes**, ensuring robust and efficient processing.

---

## Dataset

We used the **Low-Light paired dataset (LOL)** for training and evaluation:

- **Training set:** `our485`  
- **Evaluation set:** `eval15`

---

## Metrics

The quality of enhanced images is evaluated using:

- **Reference-based metrics:**  
  - PSNR (Peak Signal-to-Noise Ratio)  
  - SSIM (Structural Similarity Index)  

- **No-reference metric:**  
  - NIQE (Naturalness Image Quality Evaluator)  

The proposed method demonstrates significant improvements compared to state-of-the-art techniques.

---

```bibtex
@inproceedings{rodrigues2025cros,
  title={Low-Light Image Quality Enhancement through Bayesian Optimization using Gaussian Processes},
  author={Gabrielly F. Rodrigues and Alex B. S. Viana and Laura A. Martinho and João M. B. Cavalcanti and José L. S. Pio and Felipe G. Oliveira},
  booktitle={CROS-Brazilian Conference on Robotics},
  year={2025}
}


